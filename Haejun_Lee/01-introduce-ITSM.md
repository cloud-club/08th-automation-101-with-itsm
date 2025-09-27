## ITSM
ITSM(IT Service Management)는 조직이 IT 서비스를 고객에게 계획, 설계, 제공, 운영, 개선하는 데 사용하는 정책, 프로세스, 절차, 지침의 집합이다.

여기서 중요한 포인트는 **서비스 중심적 접근**이다.

전통적인 IT 운영은 서버, 네트워크, 애플리케이션 같은 기술적 자원 관리에 초점이 맞춰져 있었다면,

ITSM은 “이 IT 서비스가 실제로 고객(내부든 외부든)과 비즈니스에 어떤 가치를 주는가?”에 더 집중한다.

쉽게 말하면, “우리는 서버를 잘 돌리고 있다”가 아니라 “우리 서비스가 고객이 원하는 걸 안정적으로 제공하고 있는가?”를 묻는 접근이다.

### ITSM의 특징
- 서비스 관점: IT를 기술이 아닌 서비스로 정의하고, 비즈니스 전략과 직접 연결한다.

- 프로세스 기반: 서비스 요청, 인시던트 관리, 변경 관리 등 반복 가능하고 표준화된 프로세스를 기반으로 운영한다.
  
- 지속적 개선: 서비스 성과를 측정하고 개선하는 순환 구조를 따른다.

- 도구 활용: ServiceNow와 같은 ITSM 도구로 프로세스를 자동화하고 효율화한다.

개인적으로 공부하면서 느낀 건, ITSM은 그냥 “운영 매뉴얼”이 아니라 **“운영 문화”**에 가깝다. 팀 전체가 동일한 기준과 프로세스를 공유해야 하고, 그 위에 지속적 개선이 얹히는 구조라서 조직의 성숙도와도 연결된다.

### ITSM의 대표 프로세스 예시
- Incident Management (인시던트 관리): 장애 발생 시 서비스의 신속한 복구

- Problem Management (문제 관리): 근본 원인을 분석하고 재발 방지

- Change Management (변경 관리): 변경 요청을 평가·승인·추적하여 서비스 안정성 보장

- Service Request Management (서비스 요청 관리): 사용자 요청(계정 생성, 접근 권한 등) 처리

- Knowledge Management (지식 관리): 해결 방법과 정보를 문서화해 재사용

현업 사례를 보면, 인시던트 관리와 문제 관리가 제대로 분리 안 되면 “똑같은 장애가 계속 발생”하는 문제가 생긴다. 그래서 많은 기업이 ITSM을 도입하면서 이 부분을 강화한다.

### ITSM의 범위 (영향 라이프 사이클..?)
ITSM은 단순히 운영만 다루지 않는다.

계획 → 설계 → 구축 → 제공 → 지원 → 개선
모든 단계에 걸쳐 영향을 끼친다.

즉, 초기 전략 수립부터 운영 안정화, 개선까지 전 주기를 커버한다.

2주차에 병욱님이 소개해주셨던 내용을 듣고 헬프데스크와 유사한 개념인가? 하는 생각이 들었었는데 공부해보니 헬프데스크는 ITSM 중 서비스 요청 처리나 인시던트 대응의 일부에 가깝다. ITSM은 그보다 훨씬 더 큰 틀의 개념이었다.

### 전통적인 IT 운영과 ITSM의 차이 (표)
| 구분 | 전통적 IT 운영 | ITSM |
|---|---|---|
| 관리 관점 | IT 내부 중심 | 비즈니스/고객 중심 |
| 문제 해결 | 사후 대응 | 예방 및 지속적 개선 |
| 절차 | 비형식적 | 표준화 된 프로세스 |
| 관리 도구 | 개별 시스템 | ServiceNow 등 프로세스 지원 도구 |
| 과금 | IT 요소별 | 서비스 수준 별 |

표로 보면 단순 비교지만, 실제로 적용해보면 사고방식 자체가 바뀐다.
“내 서버는 잘 돌아가고 있어”에서 → “이 서비스가 고객이 원하는 SLA(Service Level Agreement)를 만족하는가?”로 관점이 이동한다.

## ITIL
ITIL(IT Infrastructure Library)은 ITSM을 구현하기 위한 가장 널리 사용되는 프레임워크다.
영국 정부의 OGC(Office of Government Commerce)가 개발했으며, 현재는 최신 버전인 ITIL 4가 활용되고 있다.

### ITIL의 핵심 개념
- 서비스 가치 시스템 (SVS, Service Value System) : IT 서비스가 어떻게 비즈니스 가치로 전환되는지를 설명하는 전체적 운영 모델

- 4가지 차원 (Four Dimensions Model)
  - 조직과 사람 (Organizations & People)
  - 정보와 기술 (Information & Technology)
  - 파트너와 공급자 (Partners & Suppliers)
  - 가치 흐름과 프로세스 (Value Streams & Processes)
  
- 서비스 가치 사슬 (Service Value Chain)
  - ITIL 4에서 제시하는 서비스 제공 활동의 핵심 구조.
  - Plan: 비전, 전략, 정책 수립
  - Improve: 지속적 개선
  - Engage: 이해관계자와의 소통 및 요구사항 파악
  - Design & Transition: 서비스 설계 및 구축
  - Obtain/Build: 서비스 컴포넌트 획득 및 개발
  - Deliver & Support: 서비스 운영 및 지원
  
여기서 인상 깊었던 건, ITIL 4는 단순 프로세스 체크리스트가 아니라 **가치 흐름** 관점을 강조한다는 점. 결국 IT 서비스의 존재 이유는 가치 전달이라는 걸 계속 환기시킨다.

### ITIL의 7가지 지침 원칙 (Guiding Principles)

1. 가치에 집중하라 (Focus on Value)

2. 있는 그대로 시작하라 (Start where you are)

3. 피드백 기반 점진적 개선 (Progress iteratively with feedback)

4. 협업하고 투명하게 일하라 (Collaborate and promote visibility)

5. 전체론적으로 사고하고 일하라 (Think and work holistically)

6. 단순하고 실용적으로 유지하라 (Keep it simple and practical)

7. 최적화하고 자동화하라 (Optimize and automate)

이걸 실제 조직에 적용한다고 상상해보면, “작게 시작해서, 투명하게 공유하고, 점진적으로 개선”하는 게 핵심 메시지다. 애자일/DevOps랑도 결이 비슷하다.

# 정리하자면,

- ITSM = IT 서비스를 관리하는 방법론 (What & Why)

- ITIL = ITSM을 구체적으로 구현하는 프레임워크 (How)

즉, ITSM이 방향성을 잡아주고, ITIL은 그걸 실행할 수 있는 실제 도구 세트에 가깝다.