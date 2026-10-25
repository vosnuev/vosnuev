<div align="center">

# 전하영

### 현장의 복잡함을 사용 가능한 시스템으로 바꾸는 사람

교직 현장에서 반복되는 문제를 직접 발견하고 해결해 온 경험을 바탕으로,  
지금은 AI 기능을 데이터 흐름·백엔드·평가·실패 처리까지 연결하고 있습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=githubpages&logoColor=white)](https://github.com/vosnuev/portfolio)
[![Attendance](https://img.shields.io/badge/Attendance-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://school-connect-attendance-2013abfd.base44.app/)
[![GitHub](https://img.shields.io/badge/GitHub-vosnuev-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vosnuev)

</div>

---

## About Me

- **문제를 기능 목록보다 먼저 봅니다.** 누가 입력하고, 누가 확인하며, 실패했을 때 무엇을 남길지부터 정리합니다.
- **AI 결과를 서비스로 연결합니다.** RAG·Agent·ML 모델을 API, 데이터 흐름, 사용자 화면과 연결하고 테스트와 평가로 확인합니다.
- **현장 언어와 개발 언어를 함께 이해합니다.** 4년간의 교직 경험을 바탕으로 실제 사용자의 맥락과 운영 제약을 구현 기준으로 바꿉니다.
- **모르는 범위를 숨기지 않습니다.** 데이터가 없으면 기능 범위를 줄이고, 팀 결과와 제 기여를 구분하며, 다음 검증 기준을 남깁니다.

## How I Work

```text
현장 관찰 → 문제와 역할 정의 → 데이터 흐름 설계 → 빠른 구현 → 테스트·평가 → 운영 기준 정리
```

## Selected Work

### [SchoolConnect Attendance](https://github.com/vosnuev/schoolconnect-attendance) — 출결 정보 흐름을 다시 설계한 웹앱

고교학점제 도입 후 여러 교사의 기록이 계속 어긋나는 문제를  
**학부모 입력 → 담임 확인·수정 → 교과교사 조회·마감** 흐름으로 재설계했습니다.

- 월 마감 누락률 **80% → 5%**, 학부모 직접 입력 **60%**
- 공유 스프레드시트의 조회·관리 한계를 웹앱의 단일 데이터 흐름으로 전환
- React · Tailwind · Base44 인증/DB/호스팅을 활용한 PWA/SPA
- 타 학급으로 확산되었고, 교직 업무 성과급 **S등급**의 근거 중 하나가 되었습니다.

### [elderly-legal-rag](https://github.com/vosnuev/elderly-legal-rag) — 답변보다 실패 지점을 먼저 찾은 RAG·Agent

- 모델·provider **12개 조합**, 평가 문항 **360개** 비교
- 오답 **405건**을 **8개 유형**으로 분류해 검색·도구·답변 문제를 구분
- 외부 MCP 도구의 fake/live 계약 테스트 **28/28 통과**
- LangSmith 추적과 평가 결과를 다음 개선 기준으로 연결

### [fashion-recommend-coordi](https://github.com/vosnuev/fashion-recommend-coordi) — 모델·API·권한을 연결한 패션 추천 서비스

- 신체치수 모델 **7종** 비교 및 추론 API 계약 정리
- 공유 옷장의 초대·방장 위임·탈퇴·동시성·검색 권한 흐름 구현
- Django 테스트 **65개**로 사용자·권한 경계를 검증
- 6인 팀 서비스 평가 **1위**, 개인 우수수료자 **30명 중 2명** 선정

### [curriculum_agent](https://github.com/vosnuev/curriculum_agent) — 교육과정 PDF를 위한 2단계 검색

교육과정 PDF에서 한 번의 검색으로 근거를 안정적으로 찾기 어려운 문제를  
Multi-Query RAG와 rerank를 결합한 2단계 검색 흐름으로 구성했습니다.

## Tools I Use

**AI / Data**  
`Python` · `RAG` · `LangChain` · `LangGraph` · `Pandas` · `scikit-learn` · `Qdrant`

**Backend / Service**  
`FastAPI` · `Django` · `REST API` · `PostgreSQL` · `React` · `Git`

---

> 기술 이름을 많이 아는 것보다, 실제 사용자가 막히는 지점과 실패 조건을 코드와 검증 기준으로 바꾸는 일을 잘하고 싶습니다.
