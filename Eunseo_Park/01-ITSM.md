### ITSM and ITIL: Principles and Framework

현재 운영은 절차와 티켓 처리 중심이다. 배포 주기는 길고, 변경 승인 회의가 병목이다. 장애 복구 시간(MTTR)은 불안정하다. IT 성과는 문서 준수로 측정되고 비즈니스 가치와 단절되어 있다.

**ITSM** 은 서비스의 기획·설계·전환·운영·개선을 엔드투엔드로 관리하는 체계이다.

**ITIL** 은 ITSM을 실행하기 위한 프레임워크이다.

**ITIL 4**는 **Service Value System(SVS)**을 통해 “수요/기회 → 가치” 흐름을 조직 활동 전반과 연결하는 운영 모델이다. 구성요소는 **Guiding Principles, Governance, Service Value Chain, Practices, Continual Improvement** 이다. 또한 **Four Dimensions(조직·사람, 정보·기술, 파트너·공급자, 가치흐름·프로세스)** 를 모든 설계와 의사결정의 공통 점검 틀로 강제한다. 실행 단위는 **34개 관리 프랙티스** 이다.

목표는 절차 준수 조직을 **가치 흐름 조직**으로 전환하는 것이다.

핵심 과업은 다음 네 가지이다.

1. **가치 흐름 정의**: 고객·비즈니스 KPI와 연결되는 서비스 가치 흐름을 SVS 기준으로 재정의하는 것이다.
2. **원칙 내재화**: 7가지 지침 원칙을 의사결정 규칙으로 제도화하는 것이다.
3. **흐름 재배선**: Service Value Chain(Plan, Engage, Design & Transition, Obtain/Build, Deliver & Support, Improve)에 맞춰 역할·입출력·승인 기준을 재설계하는 것이다.
4. **프랙티스 조립**: 34개 프랙티스를 상황에 맞게 선택·표준화하고 Four Dimensions로 리스크를 동시 점검하는 것이다.

전환 실행은 원칙→흐름→프랙티스→지표의 순서로 진행한다.

1. 원칙 내재화이다. 7가지 지침 원칙을 의사결정 기준으로 문서화하고, 변경 승인, 백로그 정제, 표준 변경 자동화, 지식 관리에 반영한다. “가치에 집중한다”, “있는 것부터 시작한다”, “점진적으로 전진하고 피드백을 수용한다”, “협업과 가시성을 높인다”, “전체론적으로 사고한다”, “단순하고 실용적으로 유지한다”, “최적화하고 자동화한다”를 검토 항목으로 고정한다.
2. 흐름 재설계이다. 현행 개발–전환–운영 핸드오버 구간을 Service Value Chain 기준으로 다시 맵핑하고, 각 활동에 필요한 입력·출력·역할·승인 기준을 정의한다. Plan과 Improve 활동을 모든 단계에 교차 배치하여 계획과 개선이 지속적으로 작동하도록 설계한다.
3. 프랙티스 조립이다. Change Enablement, Release Management, Incident/Problem Management, Service Catalog, Monitoring & Event Management, Deployment Management, Availability/Capacity Management, Knowledge Management 등을 가치 흐름 위치에 배선한다. 각 프랙티스는 목적, 절차, 산출물, 책임, 측정지표를 포함하도록 표준화한다.
4. Four Dimensions 통합 점검이다. 모든 변경안과 신규 프랙티스에 대해 역할·스킬(조직·사람), 데이터·툴 연계(정보·기술), 계약·공급자 책임(파트너·공급자), 엔드투엔드 절차와 내부 통제(가치흐름·프로세스)를 동시 검토한다.
5. 지표와 거버넌스 정렬이다. CAB는 고위험 변경에 한정하고, 저위험 표준 변경은 사전 정의 기준 충족 시 자동화한다. 목표 지표를 리드타임, 변경 실패율, MTTR, 고객 만족도로 설정하고, 분기별로 목표 상향과 병목 제거를 의무화한다.
6. 지식과 가시성 강화이다. 운영 문서와 트러블슈팅 가이드를 단일 지식 저장소로 통합하고, 관측성 지표 대시보드를 서비스 단위로 공개한다. 릴리스 노트와 서비스 수준 목표(SLO)는 비즈니스 단위에서도 해석 가능한 형태로 제공한다.

배포 리드타임은 단축되고, 표준 변경 자동화율은 상승한다. Change Failure Rate와 MTTR은 하락한다. 서비스 성과는 비즈니스 KPI와 직접 연결되며, 우선순위 결정은 가치 기준으로 일관화된다. 프랙티스는 조직 상황에 맞게 재조립 가능하며, Four Dimensions 점검으로 사일로 리스크가 감소한다. 결과적으로 운영은 문서 준수 체계에서 **가치 중심 체계**로 전환된다. ITSM의 목적과 ITIL 4의 구성요소는 조직의 일상 운영 규칙으로 정착한다.

### **ServiceNow in ITSM: Overview and Key Features**

대부분의 조직이 ITIL에 맞춰 인시던트·문제·변경·요청을 표준화하고 싶지만, 부서·툴이 제각각이라 흐름이 끊겨 효율이 떨어지는 상황이다. ServiceNow ITSM은 이런 단절을 **단일 AI 플랫폼/단일 데이터 모델**로 묶어 서비스 전달 전 과정을 일관되게 운영하게 해준다.

ITSM 코어 프로세스를 자동화하고, 승인·조달·지식·CMDB까지 연동해 **복구 속도, 변경 안정성, 자체 해결률**을 높이는 과제가 있다.
ServiceNow는 ITIL 정렬형 모듈(Incident/Problem/Change/Request/Knowledge)에 **워크플로우 엔진**과 AI(예측 지능, 가상 에이전트)를 결합하여, 생성→할당→승인→실행→검증→지식화까지를 자동화한다.

핵심 기능 ① — 서비스 카탈로그 & 승인/조달 자동화
핵심 기능 ② — 예측 지능(Predictive Intelligence) & 가상 에이전트(Virtual Agent)
핵심 기능 ③ — CMDB 기반 변경/위험/운영 가시성
핵심 기능 ④ — 커뮤니티·가이드·사례를 통한 빠른 도입

중복 입력·핸드오프 지연이 줄고, 표준화된 흐름 속에서 **MTTR 단축·변경 성공률 개선·셀프서비스 해결 증가**가 가능해진다. 고객 사례와 스토리에서 AI·자동화 도입 후 지원 품질과 속도가 개선되는 결과가 반복적으로 보고되고 있다.

ServiceNow ITSM은 **ITIL 정렬 코어 + 워크플로우 + AI/가상 에이전트 + CMDB**를 **단일 플랫폼**에서 유기적으로 붙여 **요청→승인→조달→변경→운영→지식화**를 자동화하는 솔루션이다. 결과는 **빠른 복구, 예측 가능한 변경, 높은 셀프서비스 비율, 운영 가시성 향상**이다.

### ITIL Implementation Examples with Automation

## 1) ASML — 가상 에이전트로 L1 티켓을 셀프해결로 전환한 사례

반도체 장비 기업 ASML은 전 세계 직원의 단순 IT 요청이 폭증하는 상황에서 헬프데스크 대기가 길어지는 문제가 있었다. 조직은 반복 L1 문의를 자동화하고 24/7 셀프해결 경로를 제공해야 한다는 과제를 세웠다. 이를 위해 ServiceNow의 가상 에이전트를 도입해 비밀번호 재설정, 소프트웨어 요청, KB 탐색 같은 상위 반복 항목을 대화형 플로우로 표준화하고, 의도 인식 기반으로 적절한 토픽으로 라우팅되게 만들었다. 그 결과 도입 수주 내 이용자가 빠르게 증가했고 만족도와 의도 매칭 정확도가 높아지며 L1 무인 종결 비율이 크게 올라, 에이전트는 고난도 이슈에 집중할 수 있게 되었다.

**Links:**

https://www.servicenow.com/uk/customers/asml.html

https://www.servicenow.com/content/dam/servicenow-assets/public/en-us/doc-type/resource-center/case-study/cs-asml.pdf

---

## 2) 대규모 조직에서 Predictive Intelligence로 “자동 분류/라우팅”을 정착한 패턴

대기업 ITSM에서는 할당 그룹이 수십~수백 개로 늘어나면서 초기 분류·오할당·핑퐁이 잦아지는 병목이 있었다. 운영팀은 초기 리드타임을 줄이기 위해 인시던트/요청을 자동으로 카테고리화하고 적절한 할당 그룹으로 라우팅하는 체계를 갖춰야 했다. 이에 과거 티켓 텍스트와 메타데이터로 ServiceNow의 Predictive Intelligence 모델을 학습시켜 자동 분류·자동 라우팅·유사 티켓 추천을 켰고, 라벨 품질 관리·검증셋 운영·정기 재학습으로 성능을 안정화했다. 결과적으로 1차 라우팅 정확도가 올라 MTTA/MTTR이 동반 하락하고, 팀 간 처리 일관성과 초기 대응 품질이 개선되었다.

**Links:**

https://www.servicenow.com/community/developer-blog/enhancing-service-delivery-with-servicenow-predictive/ba-p/3070551

https://www.beyond20.com/blog/servicenow-ai-and-predictive-intelligence-reducing-ticket-volumes-with-smart-automation/

https://www.servicenow.com/content/dam/servicenow-assets/public/en-us/doc-type/resource-center/white-paper/agent-intelligence.pdf

---

## 3) “요청 → 승인 → 조달(발주) → 이행” 엔드투엔드 자동화로 리드타임을 줄인 설계

하드웨어·소프트웨어·권한 요청이 폼 작성, 다단계 승인, 발주/라이선스 지급, 상태 알림으로 이어지는 반복 흐름에서 사람 손이 많이 타 병목과 누락이 발생했다. 조직은 부서·금액·코스트센터·리스크 기준으로 조건부 승인을 자동화하고, 조달/자산/CMDB까지 이어지는 전과정 자동화를 만들겠다는 목표를 잡았다. Service Catalog와 Flow Designer/Workflow로 항목을 표준화하고 승인 규칙을 코드화했으며, 조달/자산 모듈과 연계해 PO·이행 태스크를 자동 생성하고 사용자 포털에 상태 가시성을 제공했다. 그 결과 요청-승인-발주 전체 리드타임이 단축되고 추적성이 향상되어 운영 수작업이 크게 줄었고, 반복 항목은 템플릿화하여 지속개선을 가속할 수 있었다.

**Links:**

https://www.servicenow.com/products/itsm.html

https://www.servicenow.com/products/it-asset-management/what-is-service-catalog.html

---

## 4) ISS — CMDB 기반으로 변경 영향 가시성을 확보해 자동화 확장의 토대를 만든 사례(JSM)

글로벌 시설관리 기업 ISS는 다수 벤더와 국가가 얽힌 복잡한 ITSM에서 변경 영향 파악과 데이터 일관성 문제를 겪고 있었다. 목표는 구성 항목(CI)과 관계를 한눈에 파악해 변경 위험과 영향을 예측하고, 그 위에 승인·배포·상태 공유 같은 자동화를 확장하는 기반을 만드는 것이었다. Jira Service Management에 자산/CMDB 기능(Insight)을 통합해 서비스와 인프라의 관계를 모델링하고, 변경 대시보드·리치 필터로 글로벌 데이터를 한 화면에서 통제했다. 결과적으로 변경 영향 예측력이 높아지고 벤더·팀 간 협업 속도가 개선되어, 이후 승인·배포 자동화와 상태 커뮤니케이션을 안정적으로 확장할 발판이 마련되었다.

**Links:**

https://www.atlassian.com/software/jira/service-management/customers

https://www.atlassian.com/dam/jcr:780375e4-23ea-4d46-8afb-383ca23a93d7/ISS%20Case%20Study.pdf

---

## 5) Domino’s — 분산된 ITSM 툴을 단일 플랫폼으로 통합해 운영 속도를 끌어올린 사례

도미노는 국가·매장 단위로 서로 다른 ITSM 솔루션을 사용하며 자동화와 협업이 단절되는 비효율을 겪고 있었다. 조직은 단일 플랫폼으로 표준화·자동화하여 처리 속도·품질·협업을 끌어올리겠다는 과제를 세웠다. 이를 위해 Jira Service Management로 통합해 개발·IT·비즈니스가 같은 데이터와 워크플로를 사용하도록 정렬했고, 중복 입력을 제거하며 백엔드 자동화로 승인·배포·상태 공유의 흐름을 단순화했다. 그 결과 전 세계 매장의 운영 흐름이 가벼워지고, 자동화/협업 속도가 올라 서비스 제공 품질과 납기 측면의 체감 개선이 나타났다.

**Links:**

https://www.theaustralian.com.au/business/technology/how-atlassian-is-speeding-up-pizza-deliveries-and-making-better-coffee-machines/news-story/b2bfe11d27515db96dcbc49b8184c6c5

---

## 6) 벤더 무관 “첫 자동화” 로드맵 — 상위 반복 티켓부터 깎아내리는 접근

대부분의 조직은 비밀번호 초기화, 계정 잠금, VPN, 라이선스 요청 같은 상위 20% 반복 티켓이 업무를 잡아먹는 상황으로 출발한다. 목표는 L1 셀프해결 비율을 끌어올리고 초기 분류/라우팅·SLA 임계 알림·승인 자동화·KB 추천으로 사람 손이 타는 구간을 체계적으로 줄이는 것이다. 가상 에이전트/포털로 셀프서비스 플로우를 만들고, Predictive Intelligence로 분류/라우팅을 자동화하고, 시간 기반 알림과 에스컬레이션을 붙이며, 카탈로그 승인 규칙을 코드화하고, 응답 메시지에 KB 링크를 자동 첨부하는 식으로 확장한다. 이렇게 하면 무인 종결률과 처리량이 빠르게 개선되고, 인력은 고난도 이슈와 RCA 중심의 개선 작업으로 포커스를 옮길 수 있다.

**Links:**

https://www.moveworks.com/us/en/resources/blog/automation-in-itsm-use-cases-best-practices

https://www.moveworks.com/us/en/resources/blog/ai-agents-for-itsm-automation