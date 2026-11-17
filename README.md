# 👋 안녕하세요, 데이터와 사용자 경험을 연결하는 서비스 기획자 이유민입니다.

> **"사용자의 일상 속 불편함(Pain Point)을 발견하고, 직접 작동하는 프로토타입으로 해결하며 고도화합니다."**  
> 경영학 & AI융합경영학 복수전공을 바탕으로, 기획부터 화면 설계(UI/UX), Firebase 기반 데이터 구조 설계 및 클라우드 실시간 동기화까지 **End-to-End 서비스 구축 경험**을 쌓아가고 있습니다.

---

## 🚀 직접 기획·개발·운영한 개인 웹앱 생태계 (Personal Web App Ecosystem)

단순한 기능 구현에 그치지 않고, **로컬 저장(`LocalStorage`) → 클라우드 실시간 동기화(`Firebase`) → 서비스 간 데이터 연동**으로 단계적 고도화를 진행한 3종의 웹 애플리케이션입니다. *(개인 데이터 보호를 위해 소스 저장소는 비공개 운영 중입니다.)*

| 프로젝트명 | 서비스 한 줄 요약 | 핵심 UX & 데이터 고도화 내역 | 기술 스택 |
| :--- | :--- | :--- | :--- |
| **📒 UNIV-TRACKER**<br>*(KGU-tracker)* | 과목별 학사 일정·시험·공지 통합 관리 대시보드 | • **정보 위계 재설계:** 오늘 마감 / 주간 일정 자동 분류<br>• **시인성 강화:** `오늘 → 공지 → 다가오는 일정` 배치 및 Alert UI 적용<br>• **멀티 디바이스 동기화:** Firebase 연동 및 로컬 데이터 일괄 이관 | `HTML/CSS/JS`<br>`Firebase`<br>`Vercel` |
| **📝 TO-DO LIST**<br>*(이유민 TO-DO)* | 계층형 과업 관리 및 실시간 달성률 트래킹 웹앱 | • **동적 로직 개선:** 실제 등록 과업 수 기준 달성률 계산 및 `Clear!` 피드백<br>• **계층형 구조:** 상·하위 과업 완료 상태 연동, 아코디언 UI, 5개 페이징<br>• **모바일 최적화:** Enter 연속 입력, iOS 홈 화면 웹앱(PWA), JSON 백업·복구 | `HTML/CSS/JS`<br>`Firebase`<br>`LocalStorage` |
| **🌿 오늘의 마음**<br>*(Daily Mind)* | 감정·학습 회고 및 할 일 데이터 연동 라이프 로그 | • **서비스 간 데이터 연동:** `TO-DO LIST`의 당일 과업 데이터 실시간 구독·표시<br>• **기록 진입 장벽 완화:** 17종+ 다중 감정 태그 & 20종 랜덤 회고 질문<br>• **탐색·안정성 고도화:** 감정 달력, 통합 키워드 검색, Debounce 자동 저장 | `HTML/CSS/JS`<br>`Firebase v10`<br>`LocalStorage` |

---

## 💡 핵심 기획 및 문제 해결 역량 (Core Competencies)

* **1. 사용자 중심의 문제 정의 및 지속적 개선 (Iterative UX)**
  * 초기 MVP 출시 후 실제 매일 사용하면서 겪은 스크롤 피로도, 중복 입력, 진행률 계산 오류 등 구체적인 불편(Pain Point)을 정의하고 UI·로직 개선으로 해결했습니다.
* **2. 서비스 간 데이터 파이프라인 및 연동 설계 (Cross-App Sync)**
  * 개별적으로 운영하던 `TO-DO LIST`와 `오늘의 마음`에 동일한 Firebase 인증 체계를 적용하고, Firestore 실시간 구독을 통해 중복 입력 없이 일정과 감정 기록이 하나로 연결되도록 설계했습니다.
* **3. 데이터 무결성 및 백업 아키텍처 구축 (Data Reliability)**
  * 브라우저 `LocalStorage` 단일 저장의 기기 종속성과 유실 위험을 극복하기 위해 클라우드 실시간 동기화, 오프라인 이중 저장, 형식 검증을 거치는 `.json` 백업·복원 기능을 구현했습니다.

---

## 🛠 Tech & Tools

* **Planning & Design:** Notion, Figma, MiriCanvas
* **Development & Cloud:** HTML5, CSS3, Vanilla JavaScript (ES6+), Firebase (Authentication, Cloud Firestore)
* **Deployment & Version Control:** Git, GitHub, Vercel
* **Data Analysis & Certifications:** SQL / Python 기초, ADsP(데이터분석 준전문가), GTQ 포토샵 2급, ITQ/DIAT 엑셀·PPT
