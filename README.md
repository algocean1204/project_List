![header](https://raw.githubusercontent.com/algocean1204/algocean1204/main/assets/header.svg)

<div align="center">

## 📂 Project & Library List

> 프로젝트와 라이브러리를 카테고리별로 정리한 저장소입니다.

</div>

---

## 🔧 AI Platform & Library

### AlgoceanApiLib

<div>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude_SDK-191919?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/Modal_GPU-000000?style=for-the-badge"/>
</div>

AI 모델 호출을 위한 재사용 가능한 공통 서빙 라이브러리. 복잡한 환경 설정 없이 LLM API를 호출하고 GPU 배포를 자동화하는 모듈 제공 (Apache 2.0)

<a href="https://github.com/AlgoceanApiLib">
<img src="https://img.shields.io/badge/GitHub-AlgoceanApiLib-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

> **하위 모듈:**
>
> ├── **claude-choice-module** — Claude API/SDK/Sub 방식과 모델, 프롬프트를 쉽게 선택·호출하는 고성능 모듈
> <br/>
> <a href="https://github.com/AlgoceanApiLib/claude-choice-module"><img src="https://img.shields.io/badge/GitHub-claude--choice--module-181717?style=flat-square&logo=github"/></a>
>
> ├── **Modal_GPU_ez** — HuggingFace 모델을 Modal GPU에 원클릭 배포하는 연결 모듈
> <br/>
> <a href="https://github.com/AlgoceanApiLib/Modal_GPU_ez"><img src="https://img.shields.io/badge/GitHub-Modal__GPU__ez-181717?style=flat-square&logo=github"/></a>
>
> └── **Langchain-modal-gpu-ez** — LangChain 전용 Modal GPU 연결 모듈
> <br/>
> <a href="https://github.com/AlgoceanApiLib/Langchain-modal-gpu-ez"><img src="https://img.shields.io/badge/GitHub-Langchain--modal--gpu--ez-181717?style=flat-square&logo=github"/></a>

---

## 🤖 AI Service Projects

### Geulteo

<div>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</div>

Qdrant(Vector DB) 기반 하이브리드 검색 + 키워드 분석 AI 서비스. FastAPI 비동기 서버로 글쓰기 난이도 진단 및 피드백 제공

<a href="https://github.com/GeulteoProject">
<img src="https://img.shields.io/badge/GitHub-GeulteoProject-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

### Mac OCR APP

<div>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MLX-000000?style=for-the-badge&logo=apple&logoColor=white"/>
<img src="https://img.shields.io/badge/DeepSeek--OCR--2-4A90D9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PyMuPDF-333333?style=for-the-badge"/>
<img src="https://img.shields.io/badge/reportlab-FF6600?style=for-the-badge"/>
</div>

Apple Silicon(M시리즈) MLX 프레임워크에 최적화된 PDF OCR 프로그램. 하드웨어 맞춤 모델 최적화로 로컬 추론 성능 극대화

<a href="https://github.com/algocean1204/Mac_OCR_APP">
<img src="https://img.shields.io/badge/GitHub-Mac__OCR__APP-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

### AI Auto Trading

<div>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/bge--m3-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Qwen2.5--7B-764BA2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DeepSeek--R1-4A90D9?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Claude_SDK-191919?style=for-the-badge&logo=anthropic&logoColor=white"/>
</div>

LLM 5종(Bllossom, Llama, DeepSeek, Qwen, Claude) + bge-m3 임베딩 모델을 활용한 AI 기반 주식 자동매매 시스템. FastAPI 서버에서 다중 모델 라우팅 처리

<a href="https://github.com/algocean1204/Auto_Trade_v1">
<img src="https://img.shields.io/badge/GitHub-Auto__Trade__v1-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🧠 AI Research & Study

### Self LLM & Full-Fine-Tuning

<div>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Transformer-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</div>

Transformer 아키텍처를 밑바닥부터 구현. Self-Attention, Multi-Head Attention, Positional Encoding의 동작 원리를 코드 레벨에서 이해. 카카오 모델 HuggingFace 파인튜닝 포함

<a href="https://github.com/algocean1204/LLM-From-Scratch-and-FineTuning">
<img src="https://img.shields.io/badge/GitHub-LLM--From--Scratch-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

### AI_Study_LV_ALL_v1

<div>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</div>

AI/ML 전체 파이프라인 실습 — 모델 구축부터 파인튜닝까지. 자연어처리(NLP) 전반 학습 정리

<a href="https://github.com/kimtaekyu1204/AI_Study_LV_ALL_v1">
<img src="https://img.shields.io/badge/GitHub-AI__Study__LV__ALL__v1-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 👾 AI Agent & Skills

### Claude SkillBook

<div>
<img src="https://img.shields.io/badge/Claude_Code-191919?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge"/>
</div>

Claude Code 커스텀 스킬 컬렉션. 계층적 SRP(단일 책임 원칙) 기반 모듈 아키텍처 자동 설계 등 AI 도구 활용 생산성 극대화 스킬 관리

<a href="https://github.com/Claude-SkillBook-algocean">
<img src="https://img.shields.io/badge/GitHub-Claude--SkillBook-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

> **하위 모듈:**
>
> └── **Plan-Module-Architecture** — 계층적 SRP 기반 모듈 설계도 자동 생성
> <br/>
> <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white"/>
> <br/>
> <a href="https://github.com/Claude-SkillBook-algocean/Plan-Module-Architecture"><img src="https://img.shields.io/badge/GitHub-Plan--Module--Architecture-181717?style=flat-square&logo=github"/></a>

---

## 📱 Archive — 과거 프로젝트

> 메인 프로필에서 분리한 프로젝트들입니다.

### StyleLens

<div>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
</div>

3D 가상 피팅 앱 — AI 기반 의류 가상 착용 서비스

<a href="https://github.com/StyleLens">
<img src="https://img.shields.io/badge/GitHub-StyleLens-181717?style=flat-square&logo=github"/>
</a>

---

### ToEicWordList

<div>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
</div>

토익 영어 단어장 앱

<a href="https://github.com/kimtaekyu1204/ToEicWordList">
<img src="https://img.shields.io/badge/GitHub-ToEicWordList-181717?style=flat-square&logo=github"/>
</a>

---

![footer](https://raw.githubusercontent.com/algocean1204/algocean1204/main/assets/footer.svg)
