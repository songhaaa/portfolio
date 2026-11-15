
# 👋 안녕하세요, AI 개발자 김송하입니다!

> **문제를 정의하고, 직접 구현하며, 실험으로 검증하는 AI 개발자입니다.**

고려대학교 인공지능학과에서 석사 학위를 취득했으며,  
**LLM 추론, RAG·Multi-Agent, 멀티모달 AI, EEG 기반 감정인식** 분야를 중심으로 연구와 개발 프로젝트를 수행했습니다.

새로운 문제를 마주하면 기존 방법의 한계를 분석하고, 해결 방법을 설계한 뒤 직접 구현하고 검증하는 과정을 중요하게 생각합니다.

연구에서 얻은 아이디어를 실제 동작하는 시스템으로 구현하는 것에 흥미를 느끼며, 최근에는 **AI 모델의 성능 개선을 넘어 실제 사용자가 활용할 수 있는 서비스 개발**에도 관심을 넓히고 있습니다.

## 📄 Portfolio

주요 연구의 배경과 문제 정의, 제안 방법, 실험 결과 및 프로젝트 경험을 포트폴리오에 정리했습니다.

논문과 코드, 프로젝트 시연 자료에 대한 링크도 포함되어 있습니다. 📘 [포트폴리오 PDF 보기](./김송하_포트폴리오.pdf)


## 🚀 Research & Projects

### 🤖 01. RAG & Multi-Agent 기반 LLM 추론 개선

**Multi-Agent 기반 의료 QA 성능 향상 연구 | 2026**

기존 RAG가 정답을 지지하는 근거에 편향되어 검색하는 문제를 개선하기 위해, 지지·반박 근거를 함께 탐색하는 Multi-Agent 추론 구조를 설계했습니다.

- Dual-Branch Retrieval 기반 지지·반박 근거 병렬 탐색
- Evidence Scoring을 활용한 근거 평가
- Targeted Re-retrieval을 통한 부족한 근거 재탐색
- 3개 의료 QA 벤치마크에서 **평균 정확도 3.48%p 개선**

### ⚡ 02. Implicit CoT 기반 효율적인 LLM 추론

**sLLM Early-exit 추론 최적화 연구 | 2026**

기존 Implicit CoT 모델이 고정된 추론 단계를 수행하면서 발생하는 불필요한 연산을 줄이기 위해 Early-exit 구조를 설계했습니다.

- Confidence 및 Latent Consistency 기반 추론 상태 평가
- Reasoning Stability와 Answer Agreement를 활용한 종료 기준 설계
- 추론 정확도와 효율 간 균형을 비교 실험으로 검증
- 평균 정확도 **56.2%**, 추론 단계 **7.7% 감소**

### 🧠 03. EEG 기반 감정인식 및 일반화 연구

**CASPER | ICASSP 2026 제1저자 논문**

라벨이 부족한 환경에서 부정확한 의사 라벨이 반복 학습되는 문제를 해결하기 위해 신뢰도 기반 준지도 학습 알고리즘을 연구했습니다.

- Confidence Bank 기반 의사 라벨 보정
- Distance-weighted Prototype Update 설계
- 기존 SOTA 대비 정확도 **2.09%p 향상**
- ICASSP 2026 논문 게재
- 국내 특허 출원 및 소프트웨어 저작권 등록

📂 [CASPER GitHub Repository](https://github.com/songhaaa/CASPER)

**HiProCo | 계층적 프로토타입 정렬 연구**

피험자별 EEG 데이터 분포 차이를 줄이기 위한 계층적 프로토타입 정렬 방법을 연구했습니다.

- Subject-Class Prototype과 Global-Class Prototype 활용
- Contrastive Learning 기반 피험자 간 표현 정렬
- 기존 SOTA 대비 정확도 **2.32%p 향상**
- 국제 학술지 투고 및 국내 특허 출원

### 🎙️ 04. 음성 감정인식 모델 및 웹 서비스 개발

**산학연계 캡스톤 프로젝트 | 2023**

음성 데이터에서 감정 정보를 추출하고 분류하는 딥러닝 모델과 Django 기반 웹 서비스를 개발한 팀 프로젝트입니다.

- 공공 음성 데이터 수집 및 전처리
- Mel-Spectrogram 기반 특징 추출
- CNN 및 Transformer 기반 감정 분류 모델 학습
- 7개 감정 분류 정확도 약 **57%**
- Django 기반 웹 서비스 구현
- **27개 팀 중 1위, 캡스톤 프로젝트 최우수상**

### 🔗 05. Collaborative Research

다양한 공동 연구를 통해 멀티모달 표현 학습과 LLM 추론 성능 검증을 경험했습니다.

| 연구 분야 | 주요 내용 | 학술 성과 |
|---|---|---|
| Cross-subject Visual Brain Decoding | Soft Alignment 및 Subject-aware Normalization 기반 멀티모달 표현 정렬 | ACM SAC 2026 |
| EEG-to-Image Alignment | 다단계 시각 표현을 활용한 EEG-이미지 정렬 | ICASSP 2026 |
| RAG Knowledge Connection | 검색된 지식을 활용한 LLM 상식 추론 성능 개선 | EMNLP 2025 |


## 🛠️ Tech Stack

**AI / Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Programming Languages**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Development / Collaboration**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

## 🏆 Awards & Patents
- **ACM SAC 2026** — Honorable Mention in AI & Agents
- **Best Paper Award (2023)** — EEG 감정인식 연구
- **캡스톤설계 프로젝트 최우수상 (2023)** — 27개 팀 중 1위
- **국내 특허 3건 출원** — EEG 감정인식 및 시각 정보 디코딩
- **소프트웨어 저작권 등록** — CASPER

## 📬 Contact

- 📧 **Email:** [songhakim00@gmail.com](mailto:songhakim00@gmail.com)
- 💻 **GitHub:** [github.com/songhaaa](https://github.com/songhaaa)
