# Evaluation plan

All procedures below are proposed. This repository contains no experimental outcome or prespecified confirmatory trial.

## Data provenance and independence

Record the exact dataset release, source, access terms, ancestry, grouping information, and split manifest. Group related frames by their strongest available patient, examination, lesion, and source-video identity. Derivatives and paired imaging modes must stay with their original group.

Missing patient mappings limit independence claims. A different filename or file hash does not establish a different patient. Inspect exact and near duplicates, temporal neighbors, crops, and known dataset-family relationships.

Freeze evaluation data before training, threshold selection, calibration, or alert-policy tuning. Audit the known training sources of pretrained checkpoints. Unknown provenance remains a stated limitation.

## Detection and false alerts

- Measure lesion-level sensitivity with spatial matching to a reference box or mask.
- Define first visibility and measure delay to the first valid alert.
- Evaluate complete videos with negative intervals, including interruptions and poor-quality frames.
- Define false-alert episodes, merging rules, and denominators before scoring.
- Report false alerts per unit of negative observation time, episode duration, and per-procedure burden.
- Report uncertainty at the patient or procedure level, not by treating adjacent frames as independent observations.

Image-level accuracy and segmentation Dice alone do not establish useful live detection or a tolerable alert burden.

## Device measurements

Use the same frozen replay cases and settings when comparing devices. Report latency distributions for capture, preprocessing, inference, alert policy, and actual LED output. Include sustained behavior, frame drops, queue age, thermal throttling, input loss, USB reconnection, restart, and recovery from failure.

A desktop GPU result or a runtime's isolated inference figure cannot be substituted for edge-device input-to-light latency.

## Human factors and later modules

Any comparison between LED-only and localized overlays needs a separately reviewed reader-study design, representative cases, reader/case dependence, and a prospectively justified analysis and sample size. No superiority, non-inferiority, reduced fatigue, or retained clinical skill is claimed.

CADx must keep pathology-linked lesion outcomes and imaging modalities clear, and report class-level performance, calibration, coverage, and abstention. A selective classifier must report the cases it could not classify. Quality-assistance outputs must be evaluated against independent annotations; motion alone does not measure physical withdrawal speed or complete mucosal coverage.

## Reporting requirements

Each future result should identify the code commit, configuration, data-manifest hash, model hash, environment, hardware, analysis definition, uncertainty, and failure cases. Publish negative findings and limitations alongside successful tests. Confirmatory claims require an appropriately finalized protocol and any necessary ethics or regulatory review.
