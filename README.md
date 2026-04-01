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
- **Wiki (설계 문서)**: https://github.com/100-hours-a-week/14-team-dojangkok-ai/wiki  
- **Repo (AI)**: https://github.com/100-hours-a-week/14-team-dojangkok-ai  
- **Demo Video**: https://drive.google.com/file/d/1uwe1eeYu5zgqgl7nNyteZwHtJ0fY2_km/view?usp=sharing

**기간**: 2025.12 ~ 2026.02
**팀/역할**: AI 2인(본인: AI/LLM 파트) · Cloud 2인 · FE 1인 · BE 1인

**한줄소개**  
OCR → LLM 분석 → 쉬운 계약서 생성 + 체크리스트/챗봇을 제공하는 계약 보조 서비스

**My Role (AI/LLM)**  
- 문서 기반 파이프라인(OCR→LLM) 설계 및 결과 생성(마크다운) 흐름 정의  
- 라이프스타일 키워드 기반 계약 체크리스트 생성
- LM Eval Harness를 이용한 모델 평가 및 선정
- 주택 임대차 계약 분쟁 사례 청킹 → VectorDB 적재
- LLM 파인튜닝 및 성능 개선
- 칸반보드를 활용한 프로젝트 진행 상황 관리

---

### 2) 📚 Study Assistant — 학습 계획/요약/챗봇 (Hackathon)
- **Demo Video (Drive)**: https://drive.google.com/file/d/1LPZ2HeFnSiq7vH4epGwKq1_-XKy5G2x9/view?usp=sharing  
- **Org**: https://github.com/KakaoTech-Bootcamp-14  
- **Repo (AI)**: https://github.com/KakaoTech-Bootcamp-14/Hackathon-AI  

**기간**: 2025.12.17 ~ 2025.12.19  
**팀/역할**: AI 1인(본인) · Cloud 2인 · Full-Stack 2인 

**한줄소개**  
학습 PDF + 기간/시간 입력 → 목차 기반 학습계획 생성 → 오늘치 학습자료 생성 → Q&A 챗봇 제공

**My Role (AI/LLM)**  
- PDF 청킹/임베딩 → Vector DB 적재 → Top-K 근거 기반 응답 생성(RAG)  
- 일정 생성(/schedule) · 요약(/summarize) · 대화(/chat) API로 기능을 제품 흐름으로 구성  

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
- **Presentation + Demo Video (Drive)**: https://drive.google.com/file/d/1VM_IgrTpaMfypHFSUqwBAxEClP77LTST/view?usp=sharing  
- **Repo**: https://github.com/imyj1013/veriview-project  
- **Slides (Drive)**: https://drive.google.com/file/d/1x3IjUAxKAmkMV6G4wyaVRWYgceG4AMoA/view?usp=sharing  

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

