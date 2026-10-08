# Offline Polyp Detector · Public Research Edition

An early-stage, documentation-only project exploring low-resource, offline colonoscopy assistance: video capture, localization-aware polyp detection, and an external LED alert.

**Status: research planning. There is no runnable detector, trained model, demonstration, validated device, or clinical-use authorization in this repository.**

The proposed system would analyze video locally without depending on a network service during inference. Whether this architecture is practical, useful, or better than existing approaches remains to be tested. The combination of offline inference and an LED alert is not presented as a proven novelty.

## What is available

- [Architecture](docs/architecture.md): proposed capture, inference, alert, and failure-state boundaries
- [Evaluation plan](docs/evaluation-plan.md): lesion-level detection, full-video false alerts, and input-to-LED latency
- [Roadmap and status](docs/roadmap-status.md): evidence required before each future stage
- [Dataset registry](data/README.md): 33 aggregate metadata records with source, overlap, and rights caveats
- [Bibliography](references/README.md): 36 literature records, available as JSON and BibTeX
- [Safety and privacy](docs/safety-and-privacy.md), [contribution guidance](CONTRIBUTING.md), and [license scope](docs/license-and-release.md)

The registry includes alternative releases, derivatives, and excluded domains. Its 33 rows are not 33 independent patient cohorts. The bibliography describes prior work; it is not evidence that this project has reproduced those results.

## Current limits

No model training, edge-hardware benchmark, reader study, external validation, clinical deployment, or demonstrated user adoption is reported here. Published results from other projects cannot be attributed to this one. Planned measures and milestones are not achieved performance.

No patient images, videos, masks, individual records, model weights, third-party source-code copies, or paper full texts are distributed. Source and licensing summaries are a research snapshot dated 2026-10-07; this public edition was prepared on 2026-10-08. Consult each primary source for current availability and terms.

## Intended development direction

Start with reproducible, non-clinical replay using authorized de-identified or synthetic material. Establish a localization-aware baseline, measure the entire capture-to-output path, and evaluate false alerts across complete negative intervals. Histology classification and observation-quality assistance would be separate later research modules with separate evidence requirements.

A dark LED must never be interpreted as an absence of polyps or a safe examination. See the [safety boundaries](docs/safety-and-privacy.md) before using these plans.

## License

Project-owned material in this repository is available under the [MIT License](LICENSE). The license does not cover linked datasets, papers, third-party code, pretrained models, or other external material. Their owners' terms remain applicable. See [NOTICE](NOTICE.md).

## 한국어 요약

인터넷 연결 없이 내시경 영상을 분석하고 외부 LED로 용종 후보를 알리는 저비용 장치를 검토하는 공개 연구 문서입니다. 현재는 설계·자료 조사 단계이며, 실행 가능한 검출기·학습 모델·실기 시연·임상 검증 결과를 제공하지 않습니다.

아키텍처, 평가 방향, 단계별 계획, 공개 집계 데이터셋 정보와 참고문헌을 포함합니다. 실제 환자 자료·논문 전문·모델 가중치는 포함하지 않습니다. 자체 작성 자료에는 MIT 라이선스를 적용하며, 연결된 제3자 자료의 이용조건은 별도로 확인해야 합니다.
