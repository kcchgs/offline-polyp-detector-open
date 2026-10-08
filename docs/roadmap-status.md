# Roadmap and status

Status date: 2026-10-08.

## Available now

- Public architecture and evaluation-planning documents
- Dataset-family, overlap, access, and aggregate metadata registry
- Literature bibliography and links to primary sources
- Safety, contribution, and license-scope guidance

## Not available or established

- Executable detector, installation procedure, demo, or trained model
- Reproduced training or device benchmarks
- A reader study or external/clinical validation
- Medical-device authorization, clinical deployment, or demonstrated adoption

## Proposed next stages

1. Reproducible replay: establish an authorized non-clinical input and timing pipeline; define distinct device and failure states.
2. Data and baseline: resolve rights and dataset ancestry, freeze grouped splits, and document a reproducible baseline.
3. Alert and edge evaluation: compare detection, false-alert burden, and actual input-to-LED latency under identical replay conditions.
4. Separate extensions: consider CADx and quality assistance only when the necessary labels, rights, and evaluation evidence are available.
5. Independent studies: finalize appropriate protocols, oversight, sample sizes, and external test sets before drawing clinical conclusions.

These are research milestones, with no promised release dates or performance thresholds. Results and runnable artifacts should be added only after their provenance, rights, privacy, and reproducibility have been checked.
