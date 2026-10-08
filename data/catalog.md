# Dataset record summaries

Aggregate public-source metadata, snapshot 2026-10-07. This is a discovery registry, not a redistribution of data or evidence of current access. Consult [the field guide](README.md) and the original sources. All source-count and rights caveats remain applicable.

## Kvasir v1

- Possible role: CADe context
- Images/frames: 4000
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 720x576 to 1920x1072
- Modality: Upper+lower GI; mode labels unverified
- Annotations: Image labels; 8 classes
- Pathology: Not pathology-linked
- Access/terms snapshot: Direct; research/education terms
- Overlap/caveats: Kvasir/HyperKvasir family
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S001](https://datasets.simula.no/kvasir/)

## Kvasir v2

- Possible role: CADe context
- Images/frames: 8000
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 720x576 to 1920x1072
- Modality: Upper+lower GI; mode labels unverified
- Annotations: Image labels; 8 classes
- Pathology: Not pathology-linked
- Access/terms snapshot: Direct; research/education terms
- Overlap/caveats: Extends v1; SEG/HyperKvasir family
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S001](https://datasets.simula.no/kvasir/)

## Kvasir-SEG

- Possible role: CADe
- Images/frames: 1000
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 332x487 to 1920x1072
- Modality: WLI; per-frame modes unverified
- Annotations: Masks; boxes; positive only
- Pathology: No histology
- Access/terms snapshot: Direct; research/education; commercial permission
- Overlap/caveats: Kvasir v2 derived; 13 replacements; HyperKvasir overlap
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S006](https://github.com/DebeshJha/Kvasir-SEG)

## HyperKvasir

- Possible role: CADe/quality pretraining
- Images/frames: 110079
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 332-3264 wide;352-2448 high
- Modality: Upper+lower GI; WLI/NBI pairing unverified
- Annotations: 10662 labeled;99417 unlabeled;SEG subset
- Pathology: No verified pathology
- Access/terms snapshot: Direct; CC BY versus restrictive README conflict
- Overlap/caveats: Kvasir/SEG; PolypDB; InfoColon; video version discrepancy
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S012](https://github.com/simula/hyper-kvasir)

## CVC-ClinicDB

- Possible role: CADe
- Images/frames: 612
- Videos/clips: 31
- Patients: 23
- Lesions: 31
- Resolution: 384x288
- Modality: WLI
- Annotations: Masks; positive only
- Pathology: No verified histology
- Access/terms snapshot: Current CVC signed DUA
- Overlap/caveats: Entire set in EndoScene
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S019](https://pmc.ncbi.nlm.nih.gov/articles/PMC5549472/)

## CVC-ColonDB creator release

- Possible role: CADe
- Images/frames: 300
- Videos/clips: 13
- Patients: 13
- Lesions: Unknown / unverified
- Resolution: 574x500
- Modality: WLI
- Annotations: Masks; positive only
- Pathology: No verified histology
- Access/terms snapshot: Current CVC signed DUA
- Overlap/caveats: EndoScene component; 380-image benchmark version differs
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S019](https://pmc.ncbi.nlm.nih.gov/articles/PMC5549472/)

## CVC-EndoSceneStill

- Possible role: CADe/context
- Images/frames: 912
- Videos/clips: 44
- Patients: 36
- Lesions: Unknown / unverified
- Resolution: Mixed ClinicDB/ColonDB
- Modality: WLI
- Annotations: Polyp+lumen+background+specular+void masks
- Pathology: No histology
- Access/terms snapshot: Current separate terms unresolved
- Overlap/caveats: Union of ClinicDB 612 and ColonDB 300
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S019](https://pmc.ncbi.nlm.nih.gov/articles/PMC5549472/)

## CVC-300 benchmark subset

- Possible role: Historical CADe test
- Images/frames: 60
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Verify package
- Modality: WLI
- Annotations: Masks
- Pathology: No histology
- Access/terms snapshot: Repack provenance/terms unresolved
- Overlap/caveats: Not independent; do not confuse with 300 or 912
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S025](https://github.com/DengPingFan/PraNet)

## CVC-ColonDB benchmark repack

- Possible role: Historical CADe test
- Images/frames: 380
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Verify package
- Modality: WLI
- Annotations: Masks
- Pathology: No histology
- Access/terms snapshot: Current CVC DUA; mapping unresolved
- Overlap/caveats: Not 300-image creator component; hash audit needed
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S025](https://github.com/DengPingFan/PraNet)

## ETIS-LaribPolypDB

- Possible role: CADe external test
- Images/frames: 196
- Videos/clips: 34
- Patients: Unknown / unverified
- Lesions: 44
- Resolution: 1225x966
- Modality: Standard colonoscopy; mode labels unverified
- Annotations: Masks; positive only
- Pathology: No histology
- Access/terms snapshot: Historical portal; current terms unverified
- Overlap/caveats: Checkpoint training/tuning audit required
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S027](https://polyp.grand-challenge.org/ETISLarib/)

## LDPolypVideo annotated

- Possible role: CADe video
- Images/frames: 40266
- Videos/clips: 160
- Patients: Unknown / unverified
- Lesions: 200
- Resolution: 560x480 provisional
- Modality: Mode labels unverified
- Annotations: Boxes;33884 positive;6382 negative
- Pathology: No verified histology
- Access/terms snapshot: Author Drive/Baidu links; license unresolved
- Overlap/caveats: Additional103 videos861400 frames video-label-only; InfoColon reuse
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S029](https://github.com/dashishi/LDPolypVideo-Benchmark)

## PolypGen

- Possible role: CADe
- Images/frames: 8037
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 384x288 to1920x1080
- Modality: Primarily conventional colonoscopy
- Annotations: Masks+boxes;4275 negative-pool frames
- Pathology: No AD/HP/SSL labels
- Access/terms snapshot: Synapse account; CC BY text inconsistency
- Overlap/caveats: >300 patients;EndoCV2021 overlap;positive pool not all polyp-present
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S040](https://www.nature.com/articles/s41597-023-01981-y)

## REAL-Colon

- Possible role: CADe/CADx/full-procedure
- Images/frames: 2757723
- Videos/clips: 60
- Patients: 60
- Lesions: 132
- Resolution: 1920x1080 acquisition;cropped frames
- Modality: Verify frame modality
- Annotations: 351264 boxes;2415614 box-negative frames
- Pathology: AD/HP/SSL/TSA/OTHER/NO POLYP
- Access/terms snapshot: Direct Figshare;CC BY4.0
- Overlap/caveats: Temporal annotation same procedures;946GB
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S032](https://github.com/cosmoimd/real-colon-dataset)

## REAL-Colon temporal/ColonTCN

- Possible role: Withdrawal/anatomy
- Images/frames: 2757723
- Videos/clips: 60
- Patients: 60
- Lesions: Unknown / unverified
- Resolution: Same REAL-Colon
- Modality: Same REAL-Colon
- Annotations: 9 frame classes;60 CSV
- Pathology: Uses underlying REAL-Colon metadata
- Access/terms snapshot: Direct Figshare;CC BY4.0
- Overlap/caveats: Same patients as REAL-Colon;published model acausal
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S038](https://doi.org/10.6084/m9.figshare.26472913)

## SUN current release

- Possible role: CADe/CADx
- Images/frames: 158690
- Videos/clips: 113
- Patients: Unknown / unverified
- Lesions: 100
- Resolution: Verify downloaded dimensions
- Modality: WLI
- Annotations: 49136 positive;109554 negative;boxes
- Pathology: Pathology incl SSL
- Access/terms snapshot: Request;noncommercial;no redistribution
- Overlap/caveats: Original paper count152560;SUN-SEG derivative
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S043](https://doi.org/10.1016/j.gie.2020.07.060)

## SUN-SEG

- Possible role: CADe/CADx/video
- Images/frames: 158690
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: 100
- Resolution: Verify delivered version
- Modality: WLI
- Annotations: Masks/boxes/weak labels;49136 positive
- Pathology: SSL1288 frames/8 clips;HP1644;AD43945
- Access/terms snapshot: Request;noncommercial;no redistribution
- Overlap/caveats: Derived SUN;285v378 positive clips contradiction;Seen split overlaps cases
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S046](https://github.com/GewelsJI/VPS/blob/main/docs/DATA_DESCRIPTION.md)

## PICCOLO

- Possible role: CADx/CADe
- Images/frames: 3433
- Videos/clips: Unknown / unverified
- Patients: 40
- Lesions: 76
- Resolution: 854x480 or1920x1080
- Modality: 2131 WLI;1302 NBI
- Annotations: Masks;patient-independent split
- Pathology: 50AD;17hyperplasia;8cancer;1missing;no SSL class
- Access/terms snapshot: Biobank request;commercial written permission
- Overlap/caveats: Paired modalities same lesion;catalog count discrepancy
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S066](https://zenodo.org/records/4279017)

## POLAR training

- Possible role: CADx
- Images/frames: 2637
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: 1339
- Resolution: Verify release
- Modality: NBI nonmagnified
- Annotations: Boxes+lesion/patient metadata
- Pathology: 73%AD;17%HP;10%SSL
- Access/terms snapshot: Request;CC BY-NC4.0 plus extra terms
- Overlap/caveats: 555 colonoscopies;do not infer unique patient count
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S068](https://www.amc.nl/web/polar-database.htm)

## POLAR validation

- Possible role: CADx external
- Images/frames: Unknown / unverified
- Videos/clips: Unknown / unverified
- Patients: 251
- Lesions: 730
- Resolution: Verify release
- Modality: NBI
- Annotations: Lesion metadata;selected diagnosed images
- Pathology: AD473;HP99;SSL63;other groups;table sum724
- Access/terms snapshot: Request;CC BY-NC4.0 plus extra terms
- Overlap/caveats: Clinical publication subset differs;source count conflict
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S068](https://www.amc.nl/web/polar-database.htm)

## GLRC/Depeca/ISIT-UMR

- Possible role: CADx
- Images/frames: Unknown / unverified
- Videos/clips: 152
- Patients: Unknown / unverified
- Lesions: 76
- Resolution: Verify release
- Modality: Paired WLI/NBI
- Annotations: Histology+expert labels;76 cases/152 modality files
- Pathology: 40AD;21HP;15 pooled SSL/SSP+TSA
- Access/terms snapshot: Author file links;data license unresolved
- Overlap/caveats: Aliases same dataset;component of PolypsSet
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S071](https://www.depeca.uah.es/colonoscopy_dataset/)

## CVC-HDClassif 2024

- Possible role: CADx/CADe
- Images/frames: 1126
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: 471
- Resolution: HD;verify archive
- Modality: WLI
- Annotations: Masks+derived boxes;lesion-level split
- Pathology: 750AD/376nonAD images;no SSL class
- Access/terms snapshot: GIANA;current data terms/access unresolved
- Overlap/caveats: Not older1001-image count;patient independence unverified
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S072](https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2024.1417862/full)

## KUMC selected source

- Possible role: CADx
- Images/frames: Unknown / unverified
- Videos/clips: 76
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Verify source
- Modality: Verify source
- Annotations: Boxes;76 of80 sequences selected
- Pathology: 38AD/38HP sequences;pathology linkage incomplete
- Access/terms snapshot: As part PolypsSet;data terms unverified
- Overlap/caveats: Source subset of PolypsSet;not all37899 frames
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S074](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0255809)

## PolypsSet composite

- Possible role: CADe/CADx
- Images/frames: 37899
- Videos/clips: 155
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Various
- Modality: Mixed source
- Annotations: Boxes;116/17/22 sequence splits
- Pathology: 87AD/68HP sequences;pathology basis audit
- Access/terms snapshot: Harvard Dataverse;current terms unverified
- Overlap/caveats: KUMC+GIANA+CVC+GLRC
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S075](https://doi.org/10.7910/DVN/FCBUOR)

## PIBAdb

- Possible role: CADx/CADe
- Images/frames: 46070
- Videos/clips: 3000
- Patients: Unknown / unverified
- Lesions: 1176
- Resolution: Verify delivered version
- Modality: WLI/NBI
- Annotations: 31946 positive images;14124 negative;>3000clips
- Pathology: Histopathology-linked;exact classes unresolved
- Access/terms snapshot: Request;nonprofit;data terms unresolved
- Overlap/caveats: >11h;curated subsets overlap raw database
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: strictly greater than 3000
- Image count qualifier: derived 31946+14124
- Source: [S077](https://pubmed.ncbi.nlm.nih.gov/41863886/)

## ASU-Mayo challenge

- Possible role: Historical CADe
- Images/frames: Unknown / unverified
- Videos/clips: 38
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Verify release
- Modality: Verify release
- Annotations: Binary masks;20train/18test
- Pathology: No verified AD/HP/SSL classes
- Access/terms snapshot: Copyright;prior ASU agreement for other use
- Overlap/caveats: Do not conflate original19400frames/10polyps release
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S079](https://knowledge.lancashire.ac.uk/id/eprint/17023/2/17023%20Final%20Version.pdf)

## CAS-Colon

- Possible role: Withdrawal/anatomy
- Images/frames: Unknown / unverified
- Videos/clips: 78
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: High-resolution;verify native dimensions
- Modality: Verify release
- Annotations: 10 anatomical labels;1Hz frames
- Pathology: No polyp histology truth
- Access/terms snapshot: Direct Figshare;CC BY4.0
- Overlap/caveats: 9.08h;32.25GB;selected high-quality withdrawal
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S049](https://doi.org/10.6084/m9.figshare.28287929)

## InfoColon hospital component

- Possible role: View quality
- Images/frames: 119798
- Videos/clips: 164
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 488x416/528x416/654x480/720x480
- Modality: Verify release
- Annotations: 7 quality classes;1Hz labels;calibration
- Pathology: No pathology truth
- Access/terms snapshot: Synapse;data terms unverified
- Overlap/caveats: 151SNUH+13CNUH;also reuses prior public datasets
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S052](https://doi.org/10.1038/s41597-026-07060-2)

## Nerthus

- Possible role: Bowel preparation
- Images/frames: 5525
- Videos/clips: 21
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 720x576
- Modality: Conventional colonoscopy
- Annotations: 4 segmentalBBPS classes;left colon
- Pathology: No pathology truth
- Access/terms snapshot: Direct official portal;terms to verify
- Overlap/caveats: InfoColon reuse;potential source-family overlap audit
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S055](https://datasets.simula.no/nerthus/)

## EndoMapper

- Possible role: Geometry/anatomy/quality
- Images/frames: Unknown / unverified
- Videos/clips: 96
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 1440x1080;40/50fps
- Modality: Upper+lower GI
- Annotations: Calibration;268679 anatomyframes;4086toolmaskframes
- Pathology: No exhaustive pathology truth
- Access/terms snapshot: Synapse request;research;no redistribution
- Overlap/caveats: Repeatpatients;SegCol derivative;96 not all colonoscopy
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S056](https://doi.org/10.1038/s41597-023-02564-7)

## PolypDB

- Possible role: CADe multimodality
- Images/frames: 3934
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Verify release
- Modality: WLI3618;NBI146;LCI60;FICE70;BLI70
- Annotations: Masks+boxes;positive curated
- Pathology: No histology labels verified
- Access/terms snapshot: Direct OSF;dataset terms unresolved
- Overlap/caveats: 2724HyperKvasir+1200BKAI+40Karolinska
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S059](https://arxiv.org/abs/2409.00045)

## COLON long-sequence

- Possible role: CADe/full-video
- Images/frames: Unknown / unverified
- Videos/clips: 40
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: 720x480;30fps
- Modality: Standard Olympus;mode labels verify
- Annotations: ~30000positive/~400000background;train sparse masks
- Pathology: AD/HP described;SSL unresolved
- Access/terms snapshot: Public train25videos;private test15;terms unresolved
- Overlap/caveats: Not all40videos are public training
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S062](https://arxiv.org/abs/2403.00663)

## CAD-CAP

- Possible role: Excluded small bowel
- Images/frames: 25124
- Videos/clips: Unknown / unverified
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: PillCamSB3
- Modality: Capsule
- Annotations: 20000normal+5124abnormal
- Pathology: No colorectal AD/HP/SSL
- Access/terms snapshot: Current data terms unresolved
- Overlap/caveats: Exclude from colon-HDMI dataset total
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S081](https://pmc.ncbi.nlm.nih.gov/articles/PMC7035135/)

## Kvasir-Capsule

- Possible role: Excluded capsule domain
- Images/frames: 4741504
- Videos/clips: 117
- Patients: Unknown / unverified
- Lesions: Unknown / unverified
- Resolution: Capsule
- Modality: Capsule
- Annotations: 47238 medically verified frames with boxes;14 classes;remaining frames unlabeled
- Pathology: Not colorectal histology core
- Access/terms snapshot: Consult official dataset terms
- Overlap/caveats: Exclude from colon-HDMI dataset total
- Count semantics: Read caveats: exact/lower-bound/derived counts are mixed; do not sum across datasets
- Video count qualifier: see release/version caveats
- Image count qualifier: see release/version caveats
- Source: [S083](https://www.nature.com/articles/s41597-021-00920-z)
