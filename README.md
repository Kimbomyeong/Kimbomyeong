# 김보명 | Backend · Cloud · AI/ML Engineer

<div align="center">

문제를 정의하고 시스템으로 해결합니다.  
정확도보다 안전성, 모델보다 시스템 설계, 성능보다 평가 체계를 우선합니다.

<br />

<img src="https://img.shields.io/badge/Backend-Spring%20Boot%20%7C%20FastAPI-2563eb?style=for-the-badge" alt="Backend" />
<img src="https://img.shields.io/badge/Cloud-AWS%20%7C%20Docker%20%7C%20Kubernetes-f59e0b?style=for-the-badge" alt="Cloud" />
<img src="https://img.shields.io/badge/AI%2FML-NLP%20%7C%20LLM%20%7C%20Evaluation-7c3aed?style=for-the-badge" alt="AI/ML" />

</div>

---

## About Me

- 단순히 기능을 구현하는 것보다, 문제를 어떤 구조로 풀어야 안정적으로 운영되는지 먼저 고민합니다.
- 백엔드, 클라우드, AI/ML 프로젝트를 하며 시스템 경계, 데이터 흐름, 평가 방식까지 함께 설계해왔습니다.
- 특히 LLM/NLP 프로젝트에서는 모델 성능만이 아니라 정합성 검증, 출력 제어, 평가 체계를 함께 설계하는 방식에 관심이 많습니다.

### Keywords

`Spring Boot` `FastAPI` `AWS` `Docker` `Kubernetes` `NLP` `LLM` `RAG` `Evaluation` `Prompt Engineering`

---

## Tech Stack

### Backend / Infra

![Java](https://img.shields.io/badge/Java-111827?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-111827?style=flat-square&logo=springboot&logoColor=6DB33F)
![FastAPI](https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688)
![Django](https://img.shields.io/badge/Django-111827?style=flat-square&logo=django&logoColor=0C4B33)
![MySQL](https://img.shields.io/badge/MySQL-111827?style=flat-square&logo=mysql&logoColor=4479A1)
![DynamoDB](https://img.shields.io/badge/DynamoDB-111827?style=flat-square&logo=amazondynamodb&logoColor=4053D6)
![AWS](https://img.shields.io/badge/AWS-111827?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-111827?style=flat-square&logo=kubernetes&logoColor=326CE5)

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-111827?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![HuggingFace](https://img.shields.io/badge/HuggingFace-111827?style=flat-square&logo=huggingface&logoColor=FFD21E)
![OpenAI](https://img.shields.io/badge/OpenAI-111827?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-111827?style=flat-square&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-111827?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-111827?style=flat-square)

### Collaboration

![Git](https://img.shields.io/badge/Git-111827?style=flat-square&logo=git&logoColor=F05032)
![Notion](https://img.shields.io/badge/Notion-111827?style=flat-square&logo=notion&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-111827?style=flat-square&logo=jira&logoColor=0052CC)

---

## What I Focus On

### 1. Backend and System Design
- Spring Boot, FastAPI, Django 기반으로 API와 데이터 흐름을 설계하고 구현합니다.
- 단일 기능보다 서비스 경계, 워크로드 분리, 운영 안정성을 함께 봅니다.

### 2. Cloud and Deployment
- AWS 기반 인프라, 배포 자동화, 네트워크 경계, 권한 관리까지 포함한 구조 설계를 좋아합니다.
- 특히 EKS Fargate, ALB Ingress, CloudFront, IRSA 같은 운영 관점의 설계를 경험했습니다.

### 3. NLP and LLM Systems
- LLM을 단순 호출하는 것보다 평가 체계, 출력 제어, 근거 기반 응답 구조를 설계하는 데 관심이 많습니다.
- RAG, intent classification, 품질 자동평가, Hybrid AI 설계 경험이 있습니다.

---

## Featured Projects

### Hiking Planner
GPS 기반 등산 경로 기록, 최빈 경로 분석, SOS 신고 기능을 포함한 안전 관리 서비스  
`Spring Boot` `FastAPI` `MySQL` `AWS`

GitHub: [Backend](https://github.com/Hiking-Planner/HikingPlanner_BE) · [Clustering Server](https://github.com/Hiking-Planner/PythonClusteringSever)

- GPS 노이즈를 줄이기 위한 좌표 라운딩과 tolerance 기반 군집화 적용
- Spring Boot와 FastAPI를 분리해 I/O 처리와 분석 연산 워크로드를 분리
- 캡스톤 대상(1등)

### ITeaMoa
EKS Fargate 기반 서버리스 MSA로 설계한 프로젝트·스터디 매칭 플랫폼  
`AWS EKS` `Fargate` `ALB` `CloudFront` `DynamoDB` `Terraform`

GitHub: 링크 정리 중

- 서비스 경계를 `/login`, `/main`, `/feed`, `/my` 단위로 분리
- Ingress, IRSA, CloudFront 캐시 무효화까지 포함한 운영 구조 설계
- 배포 자동화와 보안 경계를 함께 고려한 클라우드 아키텍처 경험

### EZPill
임산부 맞춤 영양제 추천, Safety Gate, RAG 챗봇을 연결한 영양관리 플랫폼  
`Django` `Flask` `LangChain` `FAISS` `GPT-4`

GitHub: 링크 정리 중

- 추천 로직과 안전성 검증 계층을 분리해 위험 추천을 줄이는 구조 설계
- PDF 기반 RAG 챗봇으로 근거 중심 응답 제공
- 출력 계약과 후처리를 통해 LLM 응답의 API 연동 안정성 확보

### LLM 페르소나 기반 인터랙티브 게임
판정, 해석, 생성을 분리한 멀티 NPC 대화 엔진  
`PyTorch` `BERT` `Gemma 2` `SFT`

GitHub: 링크 정리 중

- "판정은 모델, 해석은 시스템, 생성은 LLM" 구조 설계
- 자유 텍스트를 TAG와 Delta로 변환해 게임 상태와 연결
- 자연어처리 부트캠프 플러스 최우수상(1등)

### AI 응답 품질 자동평가
대화 맥락과 응답을 입력으로 9개 품질 기준을 판정하고 OOD 안전성까지 검증한 평가 모델  
`PyTorch` `RoBERTa` `ELECTRA` `W&B`

GitHub: 링크 정리 중

- Always-Positive 퇴행을 TN, pos_rate_pred 지표로 진단
- ID 성능뿐 아니라 OOD 과신 리스크까지 함께 평가
- 모델 성능보다 운영 안전성을 중심에 둔 평가 체계 구축

### AI 강의 분석 리포트 생성기
실제 강의 데이터와 내부 품질 기준을 바탕으로 강의 품질 평가용 Hybrid AI MVP를 설계 중인 프로젝트  
`Python` `Pandas` `OpenAI` `Prompt Engineering`

GitHub: 링크 정리 중

- 실제 STT 강의 스크립트와 메타데이터 정합성 검증
- 18개 품질 평가 항목을 반영한 MVP 범위 정의
- EDA, 분석 설계, 평가 파이프라인 구조화 진행 중

---

## Experience

### AI 학습데이터 구축 및 품질 평가
**링키지랩** · 2025.10 - 2025.12

- 카카오 쇼핑 `kanana AI` 서비스 적용용 LLM 데이터 구축
- SQL/Python 기반 데이터 추출 및 전처리
- Ground Truth 데이터셋 구축 및 프롬프트 최적화 경험

### 실무형 NLP 과제 프로젝트
**멋쟁이사자처럼** · 2026.03 - 2026.04

- 실제 강의 데이터와 내부 품질 기준을 활용한 강의 분석 리포트 프로젝트
- EDA, 데이터 정합성 검증, MVP 정의, 분석 설계 진행

---

## Education

- **단국대학교 소프트웨어학과** | 2019.03 - 2025.02
- **TABA 아카데미** | 2023.09 - 2023.12
- **AWS & GBSA 클라우드/AI** | 2024.06 - 2024.09
- **전국 대학생 연합 빅데이터 학회** | 2025.03 - 2025.09
- **멋쟁이사자처럼 NLP 부트캠프** | 2025.12 - 2026.02

---

## Awards

- **캡스톤 대상(1등)** | 단국대학교 | 2024.11 | `하이킹 플래너`
- **자연어처리 부트캠프 플러스 최우수상(1등)** | 멋쟁이사자처럼 | 2026.02 | `LLM 페르소나 기반 인터랙티브 게임`

