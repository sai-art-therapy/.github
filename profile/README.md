# GDAM

AI 기반 HTP 미술심리 분석 및 보호자 양육 상담 서비스입니다.

GDAM은 아동의 HTP 그림 검사와 PDI 응답을 바탕으로 그림 특징을 분석하고,  
보호자에게 이해하기 쉬운 심리 리포트와 양육 상담 챗봇을 제공하는 서비스입니다.

## Project Overview

- HTP 그림 이미지 업로드 및 분석
- YOLO 기반 집/나무/사람 객체 탐지
- OpenCV 기반 그림 특징 추출
- PDI 질문 및 답변 흐름 제공
- RAG 기반 HTP 분석 리포트 생성
- 보호자용 육아 상담 챗봇 제공
- 검사 결과 및 채팅 기록 관리

## Repository

| Repository | Description |
|---|---|
| backend | FastAPI 기반 API 서버, 인증, DB, HTP 검사, 리포트, 챗봇 API |
| frontend | React 기반 모바일 웹 UI 및 API 연동 |
| ai | YOLO 기반 그림 분석 및 LLM 기반 리포트 생성 모듈 |
| data | HTP 데이터셋, 전처리 자료, 실험 관련 파일 |

## Tech Stack

| Area | Stack |
|---|---|
| Frontend | React |
| Backend | FastAPI, PostgreSQL, SQLAlchemy |
| AI | YOLO, OpenCV, RAG, OpenAI API |
| Vector DB | ChromaDB |
| Infra | AWS EC2, Nginx |

## System Flow

1. 보호자가 자녀 정보를 등록합니다.
2. 자녀가 HTP 그림 검사를 진행합니다.
3. 그림 이미지를 서버에 업로드합니다.
4. AI 모델이 집, 나무, 사람 객체와 시각적 특징을 분석합니다.
5. PDI 질문을 통해 그림에 대한 추가 맥락을 수집합니다.
6. 분석 결과와 PDI 응답을 바탕으로 HTP 리포트를 생성합니다.
7. 보호자는 리포트를 확인하고, 결과 기반 양육 상담 챗봇을 사용할 수 있습니다.

## Team Contribution

| Member | Role |
|---|---|
| 팀원 A | Backend API, DB 설계, RAG, OpenAI 연동, AWS 배포 |
| 팀원 B | Frontend 화면 구현 및 API 연동 |
| 팀원 C | YOLO 모델 학습 및 그림 분석 모듈 |
| 팀원 D | 데이터셋 구축 및 전처리 |
| 팀원 E | UI/UX 디자인 및 발표 자료 |


