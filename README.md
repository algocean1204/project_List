![header](https://raw.githubusercontent.com/algocean1204/algocean1204/main/assets/header.svg)

<div align="center">

## 📂 Project & Library List

> 프로젝트와 라이브러리를 카테고리별로 정리한 저장소입니다.

</div>

---

## 🔧 AI Platform & Library

### AlgoceanApiLib

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Claude_SDK-191919?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Modal_GPU-000000?style=flat-square"/>

AI 모델 서빙을 위한 재사용 가능한 플랫폼 라이브러리. 핵심 모듈은 `pip install`로 누구나 설치할 수 있는 PyPI 패키지로 배포 (Apache 2.0)

[![GitHub](https://img.shields.io/badge/GitHub-AlgoceanApiLib-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AlgoceanApiLib)

| 모듈 | 설명 | 설치 | Links |
|:-----|:-----|:-----|:-----:|
| **claude-choice-module** | Claude API/SDK/Sub 방식과 모델, 프롬프트를 쉽게 선택·호출하는 고성능 모듈 | — | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/AlgoceanApiLib/claude-choice-module) |
| **Modal_GPU_ez** | HuggingFace 모델을 Modal GPU에 원클릭 배포 | `pip install modal-gpu-ez` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/AlgoceanApiLib/Modal_GPU_ez) [![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/modal-gpu-ez/) |
| └── **Langchain-modal-gpu-ez** | LangChain 전용 Modal GPU 연결 모듈 | `pip install langchain-modal-gpu-ez` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/AlgoceanApiLib/Langchain-modal-gpu-ez) [![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/langchain-modal-gpu-ez/) |

---

## 🤖 AI Service Projects

### Geulteo

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Qdrant-DC382D?style=flat-square"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

Qdrant(Vector DB) 기반 하이브리드 검색 + 키워드 분석 AI 서비스. FastAPI 비동기 서버로 글쓰기 난이도 진단 및 피드백 제공

[![GitHub](https://img.shields.io/badge/GitHub-GeulteoProject-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/GeulteoProject/BE)

---

### Mac OCR APP

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/MLX-000000?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/DeepSeek--OCR--2-4A90D9?style=flat-square"/> <img src="https://img.shields.io/badge/PyMuPDF-333333?style=flat-square"/> <img src="https://img.shields.io/badge/reportlab-FF6600?style=flat-square"/>

Apple Silicon(M시리즈) MLX 프레임워크에 최적화된 PDF OCR 프로그램. 하드웨어 맞춤 모델 최적화로 로컬 추론 성능 극대화

[![GitHub](https://img.shields.io/badge/GitHub-Mac__OCR__APP-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/algocean1204/Mac_OCR_APP)

---

### AI Auto Trading

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/bge--m3-FF6F00?style=flat-square"/> <img src="https://img.shields.io/badge/Qwen2.5--7B-764BA2?style=flat-square"/> <img src="https://img.shields.io/badge/DeepSeek--R1-4A90D9?style=flat-square"/> <img src="https://img.shields.io/badge/Claude_SDK-191919?style=flat-square&logo=anthropic&logoColor=white"/>

LLM 5종(Bllossom, Llama, DeepSeek, Qwen, Claude) + bge-m3 임베딩 모델을 활용한 AI 기반 주식 자동매매 시스템. FastAPI 서버에서 다중 모델 라우팅 처리

[![GitHub](https://img.shields.io/badge/GitHub-Auto__Trade__v1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/algocean1204/Auto_Trade_v1)

---

## 🧠 AI Research & Study

### Self LLM & Fine-Tuning

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Transformer-FF6F00?style=flat-square"/> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>

Transformer 아키텍처를 밑바닥부터 구현. Self-Attention, Multi-Head Attention, Positional Encoding의 동작 원리를 코드 레벨에서 이해. 카카오 모델 HuggingFace 파인튜닝 포함

[![GitHub](https://img.shields.io/badge/GitHub-LLM--From--Scratch-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/algocean1204/LLM-From-Scratch-and-FineTuning)

---

### AI_Study_LV_ALL_v1

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>

AI/ML 전체 파이프라인 실습 — 모델 구축부터 파인튜닝까지. 자연어처리(NLP) 전반 학습 정리

[![GitHub](https://img.shields.io/badge/GitHub-AI__Study__LV__ALL__v1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kimtaekyu1204/AI_Study_LV_ALL_v1)

---

### LangChain + MLX Self Study

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/MLX-000000?style=flat-square&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Qwen3.5-764BA2?style=flat-square"/> <img src="https://img.shields.io/badge/DeepSeek--R1-4A90D9?style=flat-square"/>

LangChain 1.0 + Apple Silicon MLX 가속 로컬 모델로 파이프라인 설계부터 자동화까지. LCEL, RAG, Agent, 멀티모델 오케스트레이션, Memory, LangSmith, 배포 최적화 전 과정 실습

[![GitHub](https://img.shields.io/badge/GitHub-Langchain--MLX--self--study-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MLSamdasu/Langchain-MLX-self-study)

---

## 👾 AI Agent & Skills

### Claude SkillBook

<img src="https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white"/> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square"/>

Claude Code 커스텀 스킬 컬렉션. 계층적 SRP(단일 책임 원칙) 기반 모듈 아키텍처 자동 설계 등 AI 도구 활용 생산성 극대화 스킬 관리

[![GitHub](https://img.shields.io/badge/GitHub-Claude--SkillBook-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Claude-SkillBook-algocean)

| 모듈 | 설명 | Links |
|:-----|:-----|:-----:|
| **Plan-Module-Architecture** | 계층적 SRP 기반 모듈 설계도 자동 생성 (`HTML` `Markdown`) | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/Claude-SkillBook-algocean/Plan-Module-Architecture) |

---

## 📱 Archive — 과거 프로젝트

| Project | Description | Tech Stack | Links |
|:--------|:------------|:-----------|:-----:|
| **StyleLens** | 3D 가상 피팅 앱 — AI 기반 의류 가상 착용 서비스 | `FastAPI` `Spring Boot` `HuggingFace` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/StyleLens) |
| **ToEicWordList** | 토익 영어 단어장 앱 | `Flutter` `Dart` | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/kimtaekyu1204/ToEicWordList) |

---

![footer](https://raw.githubusercontent.com/algocean1204/algocean1204/main/assets/footer.svg)
