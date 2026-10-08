# Proposed architecture

This document describes a research design, not an implemented or validated system.

## Data path

Authorized de-identified or synthetic replay source → compatible video capture → timestamped frame buffer → preprocessing → localization-aware CADe inference → causal alert policy → LED command → measured light output.

A video capture interface is distinct from a computer's HDMI output. The source format, supported resolutions and frame rates, interlacing, signal compatibility, and capture behavior must be established before model benchmarking.

The primary endoscopy display should remain independent of the research device. Consumer capture devices and computers do not establish suitability for connection to patient-care equipment.

## Components and boundaries

- Capture: record source frame identity, arrival timestamp, dimensions, missing frames, and input status.
- Inference: retain boxes or masks and confidence for spatially correct scoring, even if the experimental output is LED-only.
- Alert policy: use causal timestamps and documented persistence/hysteresis rules selected on development data.
- Output: distinguish a candidate alert from ready, no-input, stale-frame, uncertain, unsupported-mode, and error states.
- Watchdog: invalidate old predictions and test restart, reconnection, and power-loss behavior.
- Research logging: collect the minimum approved timing and event information; video retention should be disabled by default.

Bound queues to prevent an apparently live alert from reflecting old frames. Report the age of the analyzed frame, not only model execution time. Final latency requires measuring the real input-to-light path.

## Training and offline inference

Training and model export would occur in a separate development environment. An approved runtime, model, and configuration would then be transferred to the experimental edge device. Local inference should not depend on an external network service.

Hardware choice remains open. Low-resource CPU and embedded GPU devices are candidate comparison classes. A benchmark must report the actual board, memory, capture interface, runtime versions, power mode, thermal conditions, input settings, and model hash. No target-device speed or stability has been measured for this public edition.

## Later modules

CADx would require pathology-linked lesion labels, modality-aware evaluation, calibration, and abstention. Observation-quality assistance would require independently annotated procedure phases and quality targets. Each module needs its own data permissions and validation. Neither is part of a released implementation here.

See the [evaluation plan](evaluation-plan.md) and [safety boundaries](safety-and-privacy.md).
