# <div align="center"> Welcome to 👨‍💻 **[imyj1013](https://github.com/imyj1013)** 's github</div>
<div align="center">

**LLM을 “데모”가 아니라 운영 가능한 서비스 기능으로 만드는 개발자**  
RAG · Vector DB · FastAPI 기반 AI 서버 · 출력 형식 안정화/후처리 · 상태/비동기 파이프라인 설계에 관심이 많습니다.

[![Email](https://img.shields.io/badge/Email-imyj1013%40gmail.com-blue?style=flat&logo=gmail&logoColor=white)](mailto:imyj1013@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-imyj1013-181717?style=flat&logo=github&logoColor=white)](https://github.com/imyj1013)

</div>

---

## ✨ About Me
- **관심 분야**: LLM 서비스화 / RAG / Vector DB / 에이전트 워크플로우
- **지향점**: 빠르게 실험하고, 지표/리스크를 정의한 뒤, 운영 가능한 구조로 고도화합니다.

---

## 🔧 Tech Stack

### AI / LLM
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![RAG](https://img.shields.io/badge/RAG-6C47FF?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-111111?style=flat)

### Backend / DB
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat&logo=mysql&logoColor=white)


---


## 📝 Projects

### 1) 🏠 DojangKok — 주택 임대차 계약 보조 서비스 (Team)
- **Repo**: https://github.com/100-hours-a-week/14-team-dojangkok-ai  
- **Demo Video**: https://drive.google.com/file/d/1uwe1eeYu5zgqgl7nNyteZwHtJ0fY2_km/view?usp=sharing

**기간**: 2025.12 ~ 2026.02

**팀/역할**: AI 2인(본인: AI 파트) · Cloud 2인 · FE 1인 · BE 1인

**한줄소개**  
전세/월세 계약이 낯선 사회초년생을 위해 계약서를 설명하고 분석해주며 계약 시에 활용 가능한 체크리스트를 생성하여 계약을 보조

**My Role (AI)**  
- **모델 평가 및 선정**: 계약서 도메인(숫자/날짜/당사자/특약) 기준으로 평가 관점 수립 및 LM Eval Harness를 이용한 후보 비교 → 운영 가능한 모델 선정
- **파이프라인 설계**: 사용자가 입력한 계약서의 S3 Presigned URL 수신 → 임시 저장 → OCR → LLM 분석 → 쉬운 계약서(Markdown) 생성 흐름 설계
- **파인튜닝(QLoRA)**: 도메인 적합도/출력 안정성 개선을 위한 QLoRA 실험 및 서빙(vLLM) 관점 검토
- **데이터셋 생성 & 분쟁사례 청킹**: 법령/가이드/분쟁사례를 사례 단위로 구조화하여 청킹 → 임베딩 → VectorDB 적재 기반 마련
- **비동기 처리/메시징(RabbitMQ)**: **Spring Boot ↔ FastAPI** 간 요청/응답을 큐로 분리하는 구조를 설계

---

### 2) 📚 Study Assistant — 학습 계획/요약/챗봇 (Hackathon)
- **Repo**: https://github.com/KakaoTech-Bootcamp-14/Hackathon-AI  
- **Demo Video**: https://drive.google.com/file/d/1LPZ2HeFnSiq7vH4epGwKq1_-XKy5G2x9/view?usp=sharing  

**기간**: 2025.12.17 ~ 2025.12.19  

**팀/역할**: AI 1인(본인) · Cloud 2인 · Full-Stack 2인 

**한줄소개**  
사용자가 입력한 학습자료(PDF)를 기반으로 학습 계획을 생성 · 오늘치 학습자료 생성 · Q&A 챗봇 제공

**My Role (AI)**  
- **파이프라인 설계**: 학습자료 PDF 청킹/임베딩 → Vector DB 적재 → Top-K 근거 기반 응답 생성(RAG)  
- **API 설계**: 일정 생성, 요약, 채팅 API 설계 및 구현

---

### 3) 🧠 Transformer(GPT-2) 구현/분석 & 파인튜닝 (Personal)
- **Report (Drive)**: https://drive.google.com/file/d/1VL1DzvB1u_Rs-DFFTk7CH-sRZgZrhCjJ/view?usp=sharing  

**기간**: 2025.11 ~ 2025.11

**한줄소개**  
Transformer 디코더 기반 언어 모델을 오픈소스를 활용해 구현하고 GPT-2 체크포인트 로딩/파인튜닝 실험 수행

**Highlights**  
- Multi-Head Attention / FFN 등 핵심 모듈 구현
- 소설 텍스트 파인튜닝 및 결과 분석/시각화

---

### 4) 💼 Verify Interview — LLM 기반 모의면접 & 채용공고 추천 (Team)
- **Presentation + Demo Video**: https://drive.google.com/file/d/1VM_IgrTpaMfypHFSUqwBAxEClP77LTST/view?usp=sharing  
- **Repo**: https://github.com/imyj1013/veriview-project  
- **Slides**: https://drive.google.com/file/d/1x3IjUAxKAmkMV6G4wyaVRWYgceG4AMoA/view?usp=sharing  

**기간**: 2025.03 ~ 2025.06  

**팀/역할**: Backend/Data 1인(본인) · AI 1인 · UI/UX 1인 · FE 1인

**한줄소개**  
구직자 포트폴리오 기반 공고 추천 + 맞춤형 모의면접을 제공하는 플랫폼

**My Role (Backend, Data)**  
- Spring Boot 기반 백엔드 전반 구현 및 모델 서버(Flask) 연동  
- TF-IDF 기반 공고 추천, JWT 인증/인가
- 채용공고 수집 및 데이터 전처리

---

## 📌 Certificates / Awards / Bootcamp
- 정보처리기사 / SQLD
- 성적우수장학금(2023-1학기 1등, 2022-2학기 3등)
- 카카오테크 부트캠프 3기 생성형 인공지능 과정(2025.09.08~2026.02.27)
