# Data Status

학습 데이터 현황 및 SDS(Scientific Document Synthetic) QA 생성 예시.

---

## Training Data

학습 데이터 상세 현황은 [DATA.md](DATA.md) 참조.

---

## SDS QA Generation Examples

SDSFramework로 과학 논문 PDF에서 자동 생성한 QA 데이터 예시 (51 sub_type 중 20종).

### Level 1: Element (단일 이미지)

#### Extraction (추출)

| | |
|---|---|
| ![EXT-VAL](example/01_EXT-VAL.png) | ![EXT-LABEL](example/02_EXT-LABEL.png) |
| **EXT-VAL** — 수치 추출 | **EXT-LABEL** — 축/범례 라벨 추출 |
| ![EXT-ENUM](example/03_EXT-ENUM.png) | |
| **EXT-ENUM** — 요소 열거/개수 | |

#### Captioning (캡션)

| | |
|---|---|
| ![CAP-FULL](example/04_CAP-FULL.png) | ![CAP-PART](example/05_CAP-PART.png) |
| **CAP-FULL** — 전체 이미지 설명 | **CAP-PART** — 구성요소 집중 설명 |

#### Reasoning (추론)

| | |
|---|---|
| ![RSN-CAUSE](example/06_RSN-CAUSE.png) | ![RSN-TREND](example/07_RSN-TREND.png) |
| **RSN-CAUSE** — 인과 분석 | **RSN-TREND** — 추세/패턴 분석 |
| ![RSN-COUNTER](example/08_RSN-COUNTER.png) | |
| **RSN-COUNTER** — 반사실 추론 | |

#### Faithfulness (검증)

| | |
|---|---|
| ![FAITH-VERIFY](example/09_FAITH-VERIFY.png) | ![FAITH-CORRECT](example/10_FAITH-CORRECT.png) |
| **FAITH-VERIFY** — True/False 검증 | **FAITH-CORRECT** — 오류 탐지+수정 |

#### Refusal (거부)

| | |
|---|---|
| ![REF-UNANS](example/11_REF-UNANS.png) | ![REF-MISLEAD](example/12_REF-MISLEAD.png) |
| **REF-UNANS** — 답변 불가 정보 요청 | **REF-MISLEAD** — 허위 전제 탐지 |

### Level 2: Page (페이지 레벨)

| | |
|---|---|
| ![PAGE-SUMM](example/13_PAGE-SUMM.png) | ![PAGE-RSN](example/14_PAGE-RSN.png) |
| **PAGE-SUMM** — 페이지 내용 요약 | **PAGE-RSN** — 요소 간 관계 추론 |

### Level 3: Cross-paper (논문 간 비교)

| | |
|---|---|
| ![CROSS-METHOD](example/15_CROSS-METHOD.png) | ![CROSS-RESULT](example/16_CROSS-RESULT.png) |
| **CROSS-METHOD** — 방법론 비교 | **CROSS-RESULT** — 성능/결과 비교 |
| ![CROSS-EVOLUTION](example/17_CROSS-EVOLUTION.png) | |
| **CROSS-EVOLUTION** — 기술 발전 추적 | |

### Level 4: Benchmark (KRETA-style)

| | |
|---|---|
| ![KRETA-S1-VALUE](example/18_KRETA-S1-VALUE.png) | ![KRETA-S2-COMPARE](example/19_KRETA-S2-COMPARE.png) |
| **S1-VALUE** — 수치 추출 (텍스트 인식) | **S2-COMPARE** — 수치 비교/순위 (추론) |
| ![KRETA-S2-TREND](example/20_KRETA-S2-TREND.png) | |
| **S2-TREND** — 추세/패턴 분석 (추론) | |
