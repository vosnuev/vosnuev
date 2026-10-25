<div align="center">

# 전하영

### AI 기능을 검증 가능한 서비스로 연결하는 개발자

RAG·Agent·ML 모델을 API, 데이터 흐름, 사용자 화면에 연결하고  
평가·테스트·실패 분석을 통해 실제로 동작하는 서비스로 만듭니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://github.com/vosnuev/portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-vosnuev-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vosnuev)

</div>

---

## About Me

| 강점 | 일하는 방식 |
| --- | --- |
| **AI 서비스 구현** | RAG·Agent·ML inference를 백엔드 API와 사용자 흐름까지 연결합니다. |
| **평가와 실패 분석** | 모델 점수 하나에 머무르지 않고 검색 실패, 도구 오류, 지연시간, 계약 불일치를 분리해 확인합니다. |
| **백엔드 설계** | 데이터 모델, API 계약, 상태 변화, 권한 경계를 서비스 동작과 함께 설계합니다. |
| **문제 재정의** | 필요한 데이터가 없거나 기술 제약이 확인되면 기능 범위와 검증 기준부터 다시 정합니다. |

## Skills

| | |
| --- | --- |
| ![AI & LLM](https://img.shields.io/badge/AI_%26_LLM-111827?style=for-the-badge&logo=openai&logoColor=white) | RAG · LangChain · LangGraph · Agent Workflow · Qdrant |
| ![Backend](https://img.shields.io/badge/BACKEND-334155?style=for-the-badge&logo=fastapi&logoColor=white) | Python · FastAPI · Django · REST API · PostgreSQL |
| ![Data & ML](https://img.shields.io/badge/DATA_%26_ML-0F766E?style=for-the-badge&logo=python&logoColor=white) | Pandas · scikit-learn · XGBoost · Model Evaluation |
| ![Service](https://img.shields.io/badge/SERVICE-374151?style=for-the-badge&logo=react&logoColor=white) | React · API Contract · Testing · Git |

## Projects

| 프로젝트 | 목적 | 나의 역할·해결 | 성과 | 드러나는 역량 |
| --- | --- | --- | --- | --- |
| [옆집손주 RAG·Agent](https://github.com/vosnuev/elderly-legal-rag) | 복지·법령 질문에 근거 기반 답변을 제공하는 Agentic RAG 서비스 | 모델·provider 벤치마크와 360문항 평가 담당<br>실패 원인을 알기 어려운 응답을 검색·도구·생성 단계로 분리하고 LangSmith 추적·MCP 계약 테스트 적용 | MCP fake/live 계약 테스트 **28/28 통과** · 오답 **405건을 8유형**으로 분류 · 평균 used tokens **17.8% 감소** | **RAG 평가 설계** · 실패 분석 · Agent 도구 연동 · 계약 테스트 |
| [COZY 패션 추천](https://github.com/vosnuev/fashion-recommend-coordi) | 신체치수·보유 의류·취향을 연결하는 AI 코디 추천 서비스 | 신체치수 모델 비교와 inference API 계약, 공유 옷장 도메인·권한 흐름 담당<br>모호한 측정·출력 정의와 공유 기능의 권한 기준을 API 계약과 상태 정책으로 구체화 | 모델 **7종 비교** · Django 테스트 **65개 통과** · 6인 팀 서비스 평가 **1위** · 개인 우수수료자 **30명 중 2명** | **ML inference** · API 설계 · 도메인 모델링 · 협업 통합 |
| [고객 이탈 예측·CEO](https://github.com/vosnuev/CEO) | 이탈 예측을 고객 유지 의사결정 흐름으로 연결 | 공개 데이터 발굴과 개인 XGBoost 분석·튜닝 담당<br>기본 임계값이 이탈 고객을 놓치는 문제를 Precision–Recall과 미탐 비용 관점에서 분석해 임계값을 0.32로 조정 | 개인 분석 실험 기준 **Recall 92.59%**, **ROC-AUC 0.9746** · 앱 리뷰 **388,918건** 데이터 확보 | **데이터 확보** · 불균형 분류 · 지표 선택 · 실험 설계 |
| [Curriculum Agent](https://github.com/vosnuev/curriculum_agent) | 교육과정 PDF에서 질문과 관련된 근거를 안정적으로 검색 | 1인 프로젝트로 문서 처리부터 검색·생성까지 구현<br>단일 검색의 근거 누락을 줄이기 위해 Multi-Query 검색 후 Cohere rerank를 적용 | Pinecone 검색·Cohere rerank·GPT-4o를 연결한 동작 가능한 RAG 프로토타입 구현 | **문서 RAG** · 검색 품질 개선 · end-to-end 구현 |
| [SchoolConnect Attendance](https://github.com/vosnuev/schoolconnect-attendance) | 여러 사용자의 출결 기록을 하나의 데이터 흐름으로 통합 | 요구사항 정의, 역할별 흐름·데이터 모델 설계, React 웹앱 제작·운영<br>분산된 기록과 책임을 입력·확인·조회 흐름으로 분리하고 단일 원천으로 통합 | 월 마감 누락률 **80% → 5%** · 학부모 직접 입력 **60%** · 타 학급 확산 | **요구사항 분석** · 데이터 모델링 · 사용자 흐름 설계 · 서비스 운영 |

## Other Projects

[Search Park](https://github.com/vosnuev/Search-Park) ·
[Shopping Assistant](https://github.com/vosnuev/Shopping_app) ·
[Subway Crowd Check](https://github.com/vosnuev/Subway_CrowdCheck) ·
[MCP Study](https://github.com/vosnuev/MCP_study) ·
[Notice Bot](https://github.com/vosnuev/notice) ·
[Score Prediction](https://github.com/vosnuev/score-prediction-analysis) ·
[TOEIC Flashcards](https://github.com/vosnuev/toeic-flashcards) ·
[Note App](https://github.com/vosnuev/Noteapp)

## How I Build

```text
문제·실패 조건 정의 → 데이터 흐름과 API 계약 설계 → 구현 → 테스트·평가 → 오류 유형화 → 다음 개선 기준 설정
```

> 모델을 연결하는 데서 멈추지 않고, 결과가 왜 맞고 어디서 실패하는지 설명할 수 있는 AI 서비스를 만듭니다.
