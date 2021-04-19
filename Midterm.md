# 중간고사 정리
- o,x문제
- 빈칸 채우기
- 단답형
- 서술형 (어떤것과 어떤것의 차이를 서술하라 1,2줄)
# 목차
  - [1.Introduction](1.introduction)
  - [2.SW_Processes](2.sw_processes)
  - [3.Critical System](3.critical-system)
  - [3.Agile SW](3.agile-sw)
  - [4.Requirements](4.requirements)  
  - [5.System modeling](5.system-modeling)  
# 1.Introduction

# 2.SW_Processes
  - Specification : 요구사항 정의
  - Design and implementation(설계 및 구현) : 시스템을 정의하고 구현
  - Validation(검증) : 요구를 수행하는지 확인
  - Evolution : 고객 변경 요구에 대한 시스템 변경
  - Plan-driven processes
    - 프로세스 활동을 미리 계획하고 진행률을 측정하는 프로세스
    - 실제로 현업에선 aglie 과 plan-driven 모두 사용한다.
  - SW processes model
    - waterfall model
      - plan-driven model 이며 개발과 계획을 분리한다.
      - 요구분석및 정의 / 구현 및 단위테스트 / 통합 및 시스템테스트 / 운영 및 유지보수
      - 장점
        - 대규모의 프로젝트에서 사용하기 용이함
        - 요구사항이 잘 정리되고 설계 과정에서의 변경이 제약적인경우
      - 단점
        - 프로세스가 진행된후의 변경이 어렵다.
        - 원칙적으로 다음단계로 이동하려면 전단계가 완료되어야한다.
    - incrementeal model
      - 개발과 계획이 뒤얽혀 있다 plan-driven 과 agile의 결합
      - 장점
        - 변화를 수용하기가 훨씬 간편하다
        - 고객의 피드백을 받기 쉽다
        - 고객에게 신속하게 배포할 수 있다.
      - 단점
        - 관리자 입장에서 프로세스의 진행도를 알기 어렵다.
        - 꾸준한 변경으로 인해 추후에 리팩토링 하기가 어렵다.
    - integration and configuration
      - 기존 컴포넌트들을 조합하여 개발 plan-driven 과 agile의 결합
      - .NET or J2EE 같은 프레임워크로 개발된 개체에 사용됨
      - Stand-alone application systems (sometimes called COTS) 라고 부름
    - Reuse-oriented sw engineering
      - 다음과 같은 순서로 처리됨
      - Requirements specification/Software discovery and evaluation/Requirements refinement/Application system configuration/Component adaptation and integration
      - 장점
        - 처음부터 개발되는 소프트웨어가 줄어 비용 및 위험 감소
        - 배포 속도 향상
      - 단점
        - 사용자의 요구사항에 충족 못할수 있음
        - 재사용될 시스템 진화를 통제할수 없음    
  - Process activities
    - Architectural design : 주요 구성요소(모듈),컴포넌트 들의 관계 및 분배 방법 설계
    - Database design : 시스템 데이터구조를 디자인 하고 db로 어떻게 표현되는지
    - Interface design : 컴포넌트들 사이의 인터페이스를 정의함
    - Component selection and design : 재사용 가능한 컴포넌트를 찾고 없는 경우 설계
    - Verification and validation (V & V) : 시스템이 사양을 만족하는지 확인하기위함
  - Coping with change
    - prototyping 전달
      - 장점
        - 시스템 사용성 up
        - 갑의 니즈에 더욱 가깝게
        - 디자인 퀄리티 up
        - 유지보수성 up
        - 개발노력을 줄일수 있다.
    - increments delivery :  우선순위를 정하여 높은 우선순위 부터 개발하여 전달
      - 장점
        - 각 기능마다 고객 에게 제공하므로 시스템을 일찍 사용해 볼수 있다.
        - 초기에 전달되는 제품은 나중 요구사항을 위한 프로토타입이 될수 있다.
        - 프로젝트 실패 위험을 감소
        - 우선순위가 높은 서비스는 가장 많이 테스팅 해볼 수 있음
      - 단점
        - 기능단위별로 제공할수 있는 공통적인 시스템이 있어야 한다.
        - 기능이 구현될때까지 모든 요구사항이 자세히 정의 되자않으므로 공통 시스템을 식별 하기 어려움
        - 특정 specification 이 개발과 함께 구현되므로 전체 요구사항과 충돌이 날 수 있다.
# 3.Critical System


# 3.Agile SW

# 4.Requirements

# 5.System modeling