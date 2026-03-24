# Training Data Overview

학습 데이터 경로: `/NetDisk/ingyu/VLM_DATA/mllm_ready`

---

## V3 (Latest)

**총 22,188,775개 QA 페어** | 6개 카테고리 | 38개 데이터셋

- **한국어**: 14,327,738 QA 페어
- **영어**: 7,861,037 QA 페어

### 카테고리 요약 — 한국어

| 카테고리 | 데이터셋 수 | QA 페어 |
|----------|-----------|---------|
| Extraction_Caption | 13 | 11,653,476 |
| Extraction_OCR | 4 | 748,053 |
| Extraction_ShortQA | 8 | 1,054,105 |
| Parsing | 4 | 278,545 |
| Reasoning | 5 | 362,691 |
| TextOnly | 1 | 230,868 |

### 카테고리 요약 — 영어

| 카테고리 | 데이터셋 수 | QA 페어 |
|----------|-----------|---------|
| Extraction_Caption | 1 | 7,666,166 |
| Extraction_OCR | 1 | 129,871 |
| Reasoning | 1 | 65,000 |

### 데이터셋 상세 — 한국어

<details>
<summary><b>Extraction_Caption</b> (13개, 11,653,476 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/s1mmalign_kor_M1_Qwen3_5_9B.jsonl` | S1-MMAlign 한국어 번역 (Qwen3.5-9B) | 7,839,542 | 10844 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_applied_kor_M0.jsonl` | AIDA 보고서 캡션 [응용/산업] | 1,379,093 | 1545 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_uncatMid_kor_M0.jsonl` | AIDA 보고서 캡션 [미분류 2011~2015] | 619,232 | 740 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_uncatLate_kor_M0.jsonl` | AIDA 보고서 캡션 [미분류 2016~2020] | 487,728 | 569 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_science_kor_M0.jsonl` | AIDA 보고서 캡션 [자연과학] | 449,566 | 535 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/kisti_hanbat_kor_M1_Qwen3_235B.jsonl` | KISTI-한밭 문서 캡션 (Qwen3-235B) | 230,463 | 1380 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_social_kor_M0.jsonl` | AIDA 보고서 캡션 [사회과학] | 188,566 | 231 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aihub_visual_kor_M0.jsonl` | AIHUB 인포그래픽 시각화 | 125,542 | 123 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/hf_llavaRecap_kor_M0.jsonl` | LLaVA 한국어 recap 120k | 119,715 | 214 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_uncatEarly_kor_M0.jsonl` | AIDA 보고서 캡션 [미분류 ~2010] | 64,894 | 81 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/hf_tableVqa_kor_M0.jsonl` | 테이블 VQA 한국어 | 59,932 | 130 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/hf_korLlava_kor_M0.jsonl` | 한국어 LLaVA 캡션 | 47,197 | 87 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/aida_humanities_kor_M0.jsonl` | AIDA 보고서 캡션 [인문/문화] | 42,006 | 45 MB |

</details>

<details>
<summary><b>Extraction_OCR</b> (4개, 748,053 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_OCR/aihub_subjectTxt_kor_M0.jsonl` | AIHUB 교과서 텍스트 OCR | 506,092 | 332 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_OCR/aihub_visual_kor_M0.jsonl` | AIHUB 인포그래픽 시각화 | 125,542 | 152 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_OCR/kisti_arxiv_kor_M0.jsonl` | 국문 arxiv 논문 OCR | 107,179 | 440 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_OCR/aihub_korProblem_kor_M0.jsonl` | AIHUB 국어 문제 OCR | 9,240 | 22 MB |

</details>

<details>
<summary><b>Extraction_ShortQA</b> (8개, 1,054,105 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_subjectTxt_kor_M0.jsonl` | AIHUB 교과서 텍스트 OCR | 506,109 | 313 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/kisti_hanbat_Vqa_kor_M1_Qwen3_235B.jsonl` | KISTI-한밭 VQA ShortQA (Qwen3-235B) | 261,496 | 327 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_visual_kor_M0.jsonl` | AIHUB 인포그래픽 시각화 | 125,542 | 70 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/kisti_hanbat_Inst_kor_M1_Qwen3_235B.jsonl` | KISTI-한밭 Instruction (Qwen3-235B) | 90,895 | 133 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_subjectImg_kor_M0.jsonl` | AIHUB 교과서 이미지 ShortQA | 43,411 | 28 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_mathMultiple_kor_M0.jsonl` | AIHUB 수학 객관식 (해설+정답) | 11,836 | 9 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_korProblem_kor_M0.jsonl` | AIHUB 국어 문제 OCR | 9,224 | 7 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_ShortQA/aihub_mathSubjective_kor_M0.jsonl` | AIHUB 수학 주관식 (해설+정답) | 5,592 | 5 MB |

</details>

<details>
<summary><b>Parsing</b> (4개, 278,545 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Parsing/hf_latexUpdate_kor_M0.jsonl` | 수식 이미지 → LaTeX 파싱 | 234,300 | 154 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Parsing/aihub_subjectImg_kor_M0.jsonl` | AIHUB 교과서 이미지 ShortQA | 43,411 | 27 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Parsing/aihub_mathMultiple_kor_M0.jsonl` | AIHUB 수학 객관식 (해설+정답) | 660 | 3 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Parsing/aihub_mathSubjective_kor_M0.jsonl` | AIHUB 수학 주관식 (해설+정답) | 174 | 1 MB |

</details>

<details>
<summary><b>Reasoning</b> (5개, 362,691 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/kisti_hanbat_kor_M1_Qwen3_235B.jsonl` | KISTI-한밭 문서 캡션 (Qwen3-235B) | 177,896 | 506 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/hf_tableVqa_kor_M0.jsonl` | 테이블 VQA 한국어 | 59,991 | 159 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/hf_chartRqa1_kor_M0.jsonl` | ChartRQA 차트 추론 (폴더 1) | 55,613 | 164 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/kisti_documen_kor_M1_gpt4o.jsonl` | KISTI 한글 문서 차트/표 QA 추론 (GPT-4o) | 35,000 | 61 MB |
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/hf_chartRqa2_kor_M0.jsonl` | ChartRQA 차트 추론 (폴더 2) | 34,191 | 99 MB |

</details>

<details>
<summary><b>TextOnly</b> (1개, 230,868 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/TextOnly/hf_yisang_kor_M0.jsonl` | 이상 문학 텍스트 전용 | 230,868 | 2107 MB |

</details>

### 데이터셋 상세 — 영어

<details>
<summary><b>Extraction_Caption</b> (1개, 7,666,166 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_Caption/s1mmalign_eng_M0.jsonl` | S1-MMAlign 영문 과학 논문 이미지 캡셔닝 | 7,666,166 | 9117 MB |

</details>

<details>
<summary><b>Extraction_OCR</b> (1개, 129,871 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Extraction_OCR/kisti_arxiv_eng_M0.jsonl` | 영문 arxiv 논문 OCR | 129,871 | 460 MB |

</details>

<details>
<summary><b>Reasoning</b> (1개, 65,000 QA)</summary>

| 파일 | 설명 | QA 페어 | 크기 |
|------|------|---------|------|
| `/NetDisk/ingyu/VLM_DATA/mllm_ready/labels/V3_llava_format/Reasoning/kisti_documen_eng_M1_gpt4o.jsonl` | KISTI 영문 문서 차트/표 QA 추론 (GPT-4o) | 65,000 | 84 MB |

</details>

---

<details>
<summary><b>V2 (Legacy)</b> (click to expand)</summary>

| 파일 | 크기 |
|------|------|
| `AIHUB_Visualization_v2_axolotl.jsonl` | 230 MB |
| `AIHUB_koreanproblem_v2_axolotl.jsonl` | 25 MB |
| `AIHUB_mathproblem_multiple_v2_axolotl.jsonl` | 19 MB |
| `AIHUB_mathproblem_subjective_v2_axolotl.jsonl` | 8 MB |
| `AIHUB_subjectmaterial_image_modify_v2_axolotl.jsonl` | 350 MB |
| `AIHUB_subjectmaterial_text_modify_v2_axolotl.jsonl` | 384 MB |
| `LaTeX-update_v2_axolotl.jsonl` | 163 MB |
| `arxiv_eng_v2_axolotl.jsonl` | 460 MB |
| `arxiv_kor_v2_axolotl.jsonl` | 439 MB |
| `image_folder_1_v2_axolotl.jsonl` | 163 MB |
| `image_folder_2_v2_axolotl.jsonl` | 99 MB |
| `kor1_YiSang_hq.jsonl` | 2042 MB |
| `llava-ko-recap-120k_v2_axolotl.jsonl` | 220 MB |
| `out-kor-llava_v2_axolotl.jsonl` | 90 MB |
| `table-VQA-ko-60k.jsonl` | 279 MB |

</details>

---

## To-Do

### 데이터 작업

- [ ] **bichallava_instruct_230k_chart 라벨 생성** — 이미지 11,997장 있으나 라벨 없음. 기존 라벨 품질 낮아 API 또는 Qwen3 vLLM으로 M1 재생성 필요

### 추후 확장

- [x] **M1 파이프라인 구축** — SDS-Engine (Qwen3.5-VL-122B-A10B-FP8) 기반 과학 문서 VQA 자동 생성 파이프라인 구축 완료, 현재 생성 중

---

*Auto-generated by `scripts/generate_data_md.py`*