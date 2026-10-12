<div align="center">

# Kim Jaeheon · AI Engineer

### RAG·AI Agent를 정량적으로 검증하고, AI 모델을 실제 서비스와 인프라로 연결합니다.

[![GitHub](https://img.shields.io/badge/GitHub-kimzaeheon--data-181717?style=flat-square&logo=github)](https://github.com/kimzaeheon-data)

</div>

## About Me

단순히 모델이나 API를 사용하는 데서 끝내지 않고, **문제를 측정 가능한 형태로 정의한 뒤 실험하고 서비스로 구현하는 과정**에 관심이 있습니다.

- 동일한 데이터와 평가셋으로 RAG 아키텍처를 비교합니다.
- 검색·생성 실패 사례를 분석하고 구조화 검색과 Agent를 조합합니다.
- Computer Vision 및 생성형 AI 모델을 API, 웹·모바일 앱과 연결합니다.
- FastAPI, Docker, GCP GPU 환경에서 추론 서비스를 구현하고 운영합니다.

## Featured Projects

### ⚽ [Footballer Scouting Agent](https://github.com/kimzaeheon-data/footballer-scouting-agent)

> EPL 선수 데이터를 위한 Naive · Router · Agentic · Cascade RAG 비교 프로젝트 · **개인 프로젝트**

자연어 축구 통계 질문에서 순수 벡터 검색이 실패하는 원인을 분석하고, 구조화 검색과 도구 사용 Agent를 직접 구현해 같은 골든셋으로 비교했습니다.

| 핵심 결과 | 수치 |
|---|---:|
| Naive RAG Retrieval Hit Rate@5 | 7.25% |
| Router RAG Answer Hit Rate | **98.55%** |
| Agentic RAG Answer Hit Rate | **98.55%** |
| Router RAG Faithfulness | **98.37%** |

`Python` `LangGraph` `LangChain` `FAISS` `BGE-M3` `OpenAI API` `pandas`

---

### 📑 [RFPilot](https://github.com/Codeit-Part3-5Team/codeit-part3-5team-project)

> 공공입찰 RFP 문서 요약·질의응답 및 의무사항 체크리스트 생성 시스템 · **팀 프로젝트**

100건의 HWP·PDF 문서를 14,606개 청크로 처리한 근거 기반 RAG 서비스입니다. Retrieval Engineer로서 임베딩 생성, Vector DB 구축 및 검색 고도화를 담당했습니다.

- Retrieval Hit Rate@5 · MRR · Context Recall: **0.940**
- Context Precision: **0.848**
- Faithfulness: **0.905**

`LangGraph` `FAISS` `BGE-M3` `FastAPI` `React`

---

### 💊 [이게머약](https://github.com/jaeheonki/medicine-object-detection-project)

> YOLO 기반 알약 인식 및 식약처 의약품 정보 조회 모바일 앱 · **팀 프로젝트**

스마트폰으로 촬영한 이미지에서 알약을 인식하고, 식약처 API를 통해 효능·복용법·주의사항을 제공하는 서비스입니다.

- mAP@0.5: **0.9914**
- mAP@0.75:0.95: **0.9811**
- F1 Score: **0.9948**

`YOLO11` `PyTorch` `FastAPI` `Flutter` `Open API`

---

### 🎨 [Ad Creative Studio](https://github.com/codeit-part4-team2/ad-creative-studio)

> 제품 보존형 AI 광고 이미지 생성 서비스 · **팀 프로젝트**

제품 사진을 유지하면서 브랜드 톤과 판매 시간대에 맞는 광고 이미지·문구를 생성합니다. ControlNet/IP-Adapter 추론 파이프라인과 GCP GPU 인프라·CUDA·배포를 담당했습니다.

`SDXL` `LoRA` `ControlNet` `IP-Adapter` `FastAPI` `Docker` `GCP` `CUDA`

## Tech Stack

| Area | Technologies |
|---|---|
| LLM / Agent | LangChain, LangGraph, OpenAI API, RAG |
| Retrieval / Data | FAISS, BGE-M3, pandas, scikit-learn |
| Vision / Generative AI | PyTorch, YOLO, SDXL, LoRA, ControlNet, IP-Adapter |
| Backend / Serving | FastAPI, Docker, GCP, CUDA, Streamlit |
| Application | Flutter, React, Next.js |

## What I Value

- **측정 가능한 개선:** 인상적인 데모보다 재현 가능한 평가를 우선합니다.
- **실패 분석:** 평균 점수뿐 아니라 어떤 질문과 조건에서 실패하는지 확인합니다.
- **End-to-End 구현:** 모델 실험에서 멈추지 않고 사용자가 만나는 서비스까지 연결합니다.
- **명확한 근거:** 과장하지 않고 데이터, 실험 조건, 한계를 함께 기록합니다.

<!-- 공개할 이메일, LinkedIn, 블로그 또는 이력서 URL이 준비되면 Contact 섹션을 추가하세요. -->

