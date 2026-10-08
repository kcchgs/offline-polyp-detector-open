# Dataset registry

This directory contains aggregate metadata and public source links, with a research snapshot dated 2026-10-07. It contains no images, videos, masks, pathology records, or patient-level manifests. Current availability and terms must be checked at the original source before use.

- [datasets.csv](datasets.csv): 33 records in UTF-8 CSV
- [datasets.json](datasets.json): the same 33 records in JSON
- [catalog.md](catalog.md): readable record summaries
- [sources.json](sources.json): 83 source IDs and public URLs

## Read the counts carefully

The 33 rows include alternative versions, derived datasets, overlapping source families, and excluded capsule-endoscopy domains. They are not 33 independent cohorts. Do not sum image, video, patient, or lesion counts across them. Counts mix exact figures, lower bounds, and derived figures; consult the qualifiers and the original source.

An empty CSV cell or JSON null means unknown or unverified, not zero. Frames are not independent patients. A lesion's morphological shape is not its pathology class. Public descriptions do not establish that this project has obtained access or downloaded the data.

## Fields

- dataset, task_role: named release and possible research role
- *_numeric: reported aggregate counts for the indicated release
- resolution, modality, annotations, pathology: source-reported scope and uncertainties
- access_and_terms: dated access/licensing summary, not legal permission
- overlap_and_caveats: shared origins, release differences, and limitations
- verified_date: prior research snapshot date, not a guarantee of current access
- count_semantics, *_qualifier: count interpretation caveats
- primary_source_id, primary_source_url: source mapping into sources.json

Known overlapping families include Kvasir/HyperKvasir, CVC/EndoScene, SUN/SUN-SEG, PolypGen/EndoCV, and REAL-Colon/ColonTCN. Establish source-aware grouping before creating train/validation/test splits.

## Rights

The repository's MIT License does not relicense any linked dataset. Public downloadability, an open-access paper, or a code license does not establish dataset or model-redistribution permission. Records retain known restrictions, unresolved terms, and source discrepancies. Actual terms and any required institutional approvals or agreements take precedence.
