<div align="center">

# 전하영

### WHY NOT? 
### AI 기능을 검증 가능한 서비스로 연결하는 개발자

RAG·Agent·ML 모델을 API, 데이터 흐름, 사용자 화면에 연결하고  
평가·테스트·실패 분석을 통해 실제로 동작하는 서비스로 만듭니다.
</div>
---

## 👋 About Me

| 강점 | 일하는 방식 |
| --- | --- |
| **AI 서비스 구현** | RAG·Agent·ML inference를 백엔드 API와 사용자 흐름까지 연결|
| **평가와 실패 분석** | 모델 점수 하나에 머무르지 않고 검색 실패, 도구 오류, 지연시간, 계약 불일치를 분리해 확인 |
| **백엔드 설계** | 데이터 모델, API 계약, 상태 변화, 권한 경계를 서비스 동작과 함께 설계 |
| **문제 재정의** | 필요한 데이터가 없거나 기술 제약이 확인되면 기능 범위와 검증 기준부터 다시 설정 |

## 🚀 Projects

### 1. [COZY; AI 패션 추천 서비스](https://github.com/vosnuev/fashion-recommend-coordi)

- **성과**
  - 모델 **7종 비교**
  - Django 테스트 **65개 통과**
  - 6인 팀 서비스 평가 **1위**
  - 개인 우수수료자 **30명 중 2명**
- **목적**
  - 신체치수·보유 의류·취향 기반 AI 코디 추천 서비스 구현
- **나의 역할**
  - 신체치수 모델 비교 및 inference API 계약 설계
  - 공유 옷장 도메인·권한 흐름 구현
  - AI·백엔드·프론트엔드 파트 간 연결

| 시행착오·문제 | 해결 방법 |
| --- | --- |
| - 제한된 신체치수에 따른 체형 설명 한계<br>- 모델별 출력 형식 차이 | - 측정값 정의 재검토<br>- inference 출력 계약 표준화<br>- 모델 7종 비교 후 적용 기준 수립 |
| - 공유 기능의 권한·동시성 기준 부재 | - 초대·탈퇴·방장 위임 상태 정의<br>- 검색·수정 권한 정책 구현<br>- Django 테스트 기반 검증 |

---

### 2. [옆집손주; 복지·법령 RAG·Agent](https://github.com/vosnuev/elderly-legal-rag)

- **성과**
  - MCP fake/live 계약 테스트 **28/28 통과**
  - 오답 **405건 → 8유형** 분류
  - 평균 used tokens **17.8% 감소**
- **목적**
  - 복지·법령 질문에 근거 기반 답변을 제공하는 Agentic RAG 서비스 구현
- **나의 역할**
  - 모델·provider 벤치마크 및 360문항 평가
  - LangSmith 기반 실행 단계 추적
  - 외부 MCP 도구 계약 테스트

| 시행착오·문제 | 해결 방법 |
| --- | --- |
| - 검색·도구·생성 오류의 혼재<br>- 그럴듯한 답변만으로 실패 지점 확인이 어려운 문제<br>- 외부 도구 연동 계약의 검증 필요 | - 검색·도구·생성 단계별 추적<br>- 오답 405건의 유형화 및 재평가<br>- 동일 계약 기준의 fake/live 테스트 설계 |

---

### 3. [고객 이탈 예측·CEO](https://github.com/vosnuev/CEO)

- **성과**
  - 개인 분석 실험 기준 **Recall 92.59%**
  - **ROC-AUC 0.9746**
  - 앱 리뷰 **388,918건** 확보
- **목적**
  - 이탈 예측을 고객 유지 의사결정 흐름으로 연결
- **나의 역할**
  - 공개 데이터 발굴
  - 개인 XGBoost 분석·튜닝
  - 임계값 민감도 및 Precision–Recall 검토

| 시행착오·문제 | 해결 방법 |
| --- | --- |
| - 기본 임계값 0.5에서 이탈 고객 미탐 증가 | - 미탐 비용 중심의 Precision-Recall 분석<br>- 의사결정 임계값 **0.32** 조정 |
| - 정확도만으로 운영 판단이 어려운 문제 | - Recall·ROC-AUC의 목적별 분리 평가<br>- 임계값 변화에 따른 결과 비교 |

---

### 4. [Curriculum Agent; 교육과정 문서 RAG](https://github.com/vosnuev/curriculum_agent)

- **성과**
  - Pinecone·Cohere rerank·GPT-4o 연동 RAG 프로토타입 구현
- **목적**
  - 교육과정 PDF에서 질문과 관련된 근거를 안정적으로 검색
- **나의 역할**
  - 문서 처리부터 검색·생성까지 1인 구현
  - 검색 결과 품질 개선 흐름 설계

| 시행착오·문제 | 해결 방법 |
| --- | --- |
| - 단일 질의 검색에서 관련 근거 누락 | - Multi-Query 기반 검색 범위 확장 |
| - 검색 결과의 우선순위 품질 한계 | - Cohere rerank 기반 근거 재정렬 |

---

### 5. [SchoolConnect Attendance; 출결 관리 웹앱](https://github.com/vosnuev/schoolconnect-attendance)

- **성과**
  - 월 마감 누락률 **80% → 5%**
  - 학부모 직접 입력 **60%**
  - 타 학급 확산
- **목적**
  - 여러 사용자의 출결 기록을 하나의 데이터 흐름으로 통합
- **나의 역할**
  - 요구사항 정의 및 역할별 사용자 흐름 설계
  - 데이터 모델 설계
  - React 기반 웹앱 제작·운영

| 시행착오·문제 | 해결 방법 |
| --- | --- |
| - 사용자별 기록 분산과 책임 불명확<br>- 월 마감 누락률 80% 문제 | - 입력·확인·조회 책임의 역할별 분리<br>- 단일 데이터 원천 기반 흐름 설계 |

## 🧰 Skills

![AI & LLM](https://img.shields.io/badge/AI_%26_LLM-0F766E?style=for-the-badge&logo=openai&logoColor=white) RAG · LangChain · LangGraph · Agent Workflow · Qdrant  
![Backend](https://img.shields.io/badge/BACKEND-1E3A5F?style=for-the-badge&logo=fastapi&logoColor=white) Python · FastAPI · Django · REST API · PostgreSQL  
![Data & ML](https://img.shields.io/badge/DATA_%26_ML-D97706?style=for-the-badge&logo=python&logoColor=white) Pandas · scikit-learn · XGBoost · Model Evaluation  
![Service](https://img.shields.io/badge/SERVICE-7C3AED?style=for-the-badge&logo=react&logoColor=white) React · API Contract · Testing · Git

## 🔗 Other Projects

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

[Note App](https://github.com/vosnuev/Noteapp)

## How I Build

```text
문제·실패 조건 정의 → 데이터 흐름과 API 계약 설계 → 구현 → 테스트·평가 → 오류 유형화 → 다음 개선 기준 설정
```

> 모델을 연결하는 데서 멈추지 않고, 결과가 왜 맞고 어디서 실패하는지 설명할 수 있는 AI 서비스를 만듭니다.
