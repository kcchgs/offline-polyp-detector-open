# Safety and privacy

This project is at the research-planning stage. It provides no validated device or clinical-use authorization. Any implementation based on these plans should begin with authorized de-identified or synthetic replay material in a non-clinical setting.

## Interpretation limits

- A dark, green, or inactive LED does not establish absence of polyps, a safe examination, or examination completeness.
- No input, stale frames, unsupported modes, abstention, and device failure must be distinguishable from a working detector.
- Proposed histology outputs cannot be used here to direct resection, leave lesions in place, omit pathology, or set surveillance intervals.
- The primary examination display must remain independent of a research device's failure.
- Connecting equipment in patient care requires separate review of ethics, regulation, electrical safety, signal routing, infection control, installation, and clinical responsibility.

## Public repository boundary

Only project-owned writing, aggregate dataset descriptions, bibliographic metadata, and source links are included. Do not add patient or procedure videos, frames, DICOM, individual pathology records, linkage tables, identifiable screenshots, institutional confidential material, credentials, or private communications.

Research manifests with individual-level identifiers belong in an appropriately approved, access-controlled environment. This public registry includes published aggregate counts only. Those counts must not be used to attempt re-identification.

## Before each release

Inspect every staged file and diff. A .gitignore is a secondary safeguard and does not protect files already tracked or secrets under unexpected names. Review dependency and data rights independently from privacy. Use synthetic examples in tests and documentation.

If sensitive material is exposed, stop further sharing and follow the relevant institutional privacy/security process. Deleting a file alone does not revoke a credential or erase previously copied content.
