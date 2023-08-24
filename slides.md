---
theme: seriph
colorSchema: dark
fonts:
  sans: Noto Sans Korean
  serif: Noto Serif Korean
  mono: Fira Code
title: INFCON 2023 후기
transition: slide-left
---

# INFCON 2023 후기

\#성장 \#환경 \#조직 \#아키텍처 

2023\. 08\.

<!--

-->

---
layout: image-right
transition: fade-out
image: /static/images/infcon-001.jpeg
---

# INFCON 2023

개발과 관련된 방대한 주제

https://inflearn.com/conf/infcon-2023

2023년 8월 15일 9시 ~ 18시

참가인원 1,800 명

연사 40 여명

---
layout: section
---

# 성장

---

# 성장이란 무엇인가

인프콘의 연사들은 성장에 대해 어떤 말을 하였나?

<v-clicks>

- 전문가가 되는 것

- 능동적인 노력이 필요한 것

- 새로운 경험과 그것이 익숙하게 되는 여정

- 일단 하기로 마음먹었으면 무슨 일이 있어도 한다

</v-clicks>

<br>

<v-click>

### 의도적으로 경험과 숙달을 반복해 전문가가 되는 것

</v-click>

---
layout: two-cols
---

# 어떻게 성장하는가?

<div v-click="1">

- '무엇'을 공부해야 하나?

</div>

<div v-click="3">

- '무엇'보다는 '잘' 배우는 힘이 중요 <h3><mdi-arrow-right-thick />학습능력</h3>

- 학습능력은 '어떻게' 키워야 하나?

</div>

::right::

<div v-click="2">

![](/static/images/infcon-002.jpeg)

</div>

---
layout: fact
---

# Routine

꾸준히 할 수 있는 힘

---

# 배우는 방법

쉽게, 자주, 견디면서?

<v-clicks>

- 한번 푼 문제를 TDD 로 다시 풀면서 TDD 를 익혀볼 수 있다. - 켄트 벡

- 만약 어떤게 어렵다면 자주 해라 - 마틴 파울러

- 고통의 계곡을 견딜 수 있어야 한다

</v-clicks>

---

# 드라이퍼스 모델 Dreyfus Model

드라이퍼스 모델이란 기술 습득의 5단계 모델

- 초보자: 매뉴얼대로 실행, 판단 불가
- 초중급자: 업무수행에 자신만의 방법
- 능숙자: 문제해결, 업무의 우선순위 판단
- 숙련자: 상황의 우선순위 판단, 맥락 이해
- 전문가: 규칙을 넘어 상황을 직관적으로 판단

---

# 주니어, 시니어, 그리고 ...

조직에서 요구하는 것이 다르다

<v-click>

- 주니어: 주어진 일을 일정안에 수행
- 시니어: 일의 완결성, 품질, 팀에 기여

</v-click>

<v-click>

- 스태프 엔지니어: 기술문화 선도, 타직군 의사소통, 조직의 성공

</v-click>

---
layout: two-cols
---

# 스태프 엔지니어

조직 레벨의 기술적 가치를 리드하는 사람

<v-click>

- 역할
  - Tech Radar: 새로운 기술에 대한 평가 및 적용
  - Fleet Management: 서비스간 의존관계 정리
  - Sound Check: 품질의 정의 및 관리, 품질측정 자동화, 도구제공(대시보드)

</v-click>

<v-click>

- 스태프 엔지니어 - 윌 라슨
- 개발자를 넘어 기술 리더로 가는 길 - 타냐 라일리

</v-click>

::right::

<v-click>

![](/static/images/staff-engineer.jpeg)

</v-click>

---
layout: section
---

# 성장 사례

스프링으로 더 나은 개발자 되기

---
layout: two-cols
---

# 기술로 성장할 수 있을까?

스프링을 선택하기까지

<div v-click="1">

- 기술의 등장배경
  - EJB 의 대안
  > https://www.wiley.com/en-au/Expert+One+on+One+J2EE+Design+and+Development-p-9780764543852 - 로드 존슨

</div>

<div v-click="2">

- 존경하는 개발자의 추천
  > 컨플루언스 개발에 스프링을 활용하고 있는데 좋은거 같다 - 마이크 캐논 브룩스

</div>

<div v-click="3">

- 공식문서, 튜토리얼, 소스코드

</div>

::right::

<div v-click="1">

![](/static/images/spring-002.jpeg)

</div>

---

# 스프링의 장점들

개발이 너무 잘 돼

<v-click>

- 시간이 지나도 기능이 변해도 코드를 파악하기 어렵지 않음 <mdi-arrow-right-thick /> 생산성이 유지

- 기술에 대한 생각이 사라짐(기술이 의식되지 않음) <mdi-arrow-right-thick /> 도메인에 집중

</v-click>

<v-click>

## 왜 잘 될까?

</v-click>

<br>

<v-click>

### 스프링의 목표

POJO 를 이용해 복잡한 서비스를 선언적이고 비침투적으로 구현하는 것

</v-click>

<br>

<v-click>

### 스프링이 강조하는 DI/IoC 가 도대체 무엇이고, 내 코드에 어떤 영향을 미치나?

</v-click>

---

# DI 와 IoC

DI/IoC 는 객체지향 설계윈칙에 충실하기 위해 나온 것

DI/IoC 에 대한 설명
- Inversion of Control Containers and the Dependency Injection pattern
  > https://martinfowler.com/articles/injection.html
- InversionOfControl
  > https://martinfowler.com/bliki/InversionOfControl.html

---
layout: fact
---

## IoC

라이브러리와 구분되는 프레임워크의 특징, 기능은 개발자가 만들고, 호출은 프레임워크가 한다

## DI
스프링에서 구동되는 특별한 IoC, 스프링에서는 어떤 제어를 역전하는가? <mdi-arrow-right-thick /> 의존성

---

# 스프링에서 DI/IoC 를 구현한 방법

<v-clicks>

- 구현과 구성의 분리
  - 구현: POJO
  - 구성: 컨테이너

- 디자인 패턴
  - 전략패턴: 디스패처 서블릿
    - 기존의 코드를 건드리지 않고 기능을 무한히 확장할 수 있음
  - 데코레이터패턴, 프록시패턴: AOP

</v-clicks>

<br>

<v-click>

### 외부의 변화를 감당하면서 흔들리지 않는 견고한 설계 <mdi-arrow-right-thick /> 객체지향 설계

</v-click>

---
transition: fade-out
---

# 스프링으로 성장하기

<v-clicks>

- 탐구
  - 스프링의 철학 <mdi-arrow-right-thick /> 스프링의 설계방식 <mdi-arrow-right-thick /> 디자인 패턴과 객체지향 설계

- 훈련과 개선
  - 튜토리얼 예제 따라하기
  - 연습용 애플리케이션 

- 테스트
  - TDD: 스프링의 소스코드에 있는 테스트 코드
  - 학습 테스트

- 공유와 논쟁
  - 고민을 통해 선택, 내가 한 선택에 대한 이유 <mdi-arrow-right-thick /> 나만의 정리법 찾기, 검색이 용이하게 <mdi-arrow-right-thick /> 글로 표현

</v-clicks>

---
layout: section
---

# 환경

---

# SW

<v-clicks>

- SW 의 품질을 높여두면 향후 기능 변경 비용이 적음 <mdi-arrow-right-thick /> 설득 어려움

- 항상 품질이 중요? <mdi-arrow-right-thick /> 품질은 범위, 시간, 비용으로 결정되는 것

- 환경의 변화 <mdi-arrow-right-thick /> 사전설계만큼 리팩토링 중요

- SW 의 가치란
  - 요구사항을 만족하는 '행위'
  - 향후 요구사항에 대응하는 '구조'

- 동작하게 만들고 '반드시' 올바른 구조로 만든다. 그리고 다음 동작을 만든다.
  > 처음에 동작하게 만들고 그 다음에 좋은 구조를 만들어라 - 켄트벡
  - 아주 작은 단위로 반복한다

</v-clicks>

---
layout: fact
---

# TDD

Test-Driven Development

---

# 일하는 방식

<v-clicks>

- 추적가능성, 검색용이성 <mdi-arrow-right-thick /> 문서화
- 놀래키지 말자 <mdi-arrow-right-thick /> 이슈사항 사전 공유

- 팀원들 동기부여
  - 좌절을 준비해라: 자신의 동기부여도 힘들데 다른 사람을?
  - 모범이 되어라: 따라하고 싶은 사람이 되어라
  - 하지마라: 호기심이나 경력개발만을 위한 기술 의사결정

- 코드리뷰
  - Best Practice 보여준다 <mdi-arrow-right-thick /> 가독성
  - 거절이 가능한 작은 단위로
  - 필요한 것만

</v-clicks>

---

# 일하는 방식 - 협업

<v-clicks>

- 조직구조에 따라 협업하는 방식이 다르다

- '무엇'과 '언제까지' 는 조직의 협의사항 <mdi-arrow-right-thick /> 커뮤니케이션을 배워라

- '어떻게' 는 우리의 선택 <mdi-arrow-right-thick /> TDD, 코드리뷰, 리팩토링 해라

</v-clicks>

<br>

<v-click>

### 우리의 전문성을 발휘하는데 허락이 필요한가? - 백명석

</v-click>

---

# 성과

무엇이 성과인가?

당신은 다른 사람의 성공에 어떻게 기여했나요? - 사티아 나델라

<v-clicks>

- 가장 중요한 기능 개발

- 코드리뷰, 짝프로그래밍 1:1, 몹프로그래밍 1:n

</v-clicks>

---
transition: fade-out
---

# 혁신

혁신은 다양성이 시킨다

<v-clicks>

- 왜 타인을 돕는 것이 중요한가? <mdi-arrow-right-thick /> 다양성이 중요하기 때문

- 왜 다양성이 중요한가? <mdi-arrow-right-thick /> 혁신은 다양성에서 나오기 때문

- 왜 혁신이 중요한가? <mdi-arrow-right-thick /> 변화하는 환경으로부터 생존하기 위해

</v-clicks>

<br>

<v-click>

### 혁신을 위한 방법

</v-click>

---
layout: section
---

# 조직구조

---
layout: two-cols
---

# 스포티파이 모델

애자일 활성화를 위한 조직 <mdi-arrow-right-thick /> 혁신

<v-click>

- 비즈니스 속도 유지, 의사결정 속도 <mdi-arrow-up />
- 팀간 종속성 최소화
- SQUAD: PM, 기획자, 디자이너, 개발자 조직
- CHAPTER: 전문영역별 조직

</v-click>

<v-click>

- 문제점
  - 장기적인 품질과 조직안정성 <mdi-arrow-down />
  - 기술책임자 부재 <mdi-arrow-right-thick /> Engineering Manager

</v-click>

::right::

![](https://i0.wp.com/congruentagile.com/wp-content/uploads/2013/02/spotify.jpg)

---

# 조직구조의 지향점

협력적 문화를 가진 혁신 조직: 높은 목적성과 자율성

![](/static/images/agile-organization.png)

---
layout: two-cols
---

# 팀 토폴로지

- 팀 유형
  - Stream-Aligned Team: 낚시를 한다
  - Enabling Team: 낚시 방법 고민
  - Complicated Subsystem Team: 참치팀
  - Platform Team: 낚시 도구 관리/개선

- 팀간 상호작용
  - 협력 Collaboration: 함께 일한다.
  - 촉진 Facilitating: 다른 팀을 지원하거나 지원받는다.
  - X-as-a-Service: 무엇인가를 제공하거나 소비한다.

::right::

![](https://image.yes24.com/goods/96362958/XL)

---
layout: section
---

# 아키텍처

---

# MSA

모놀리식과 마이크로 사이

<v-click>

소프트웨어 구조는 해당 소프트웨어를 개발한 조직의 커뮤니케이션 구조를 닮게 된다. - 콘웨이의 법칙

</v-click>

<v-clicks>

- 비즈니스에 맞는 서비스 크기
  - 너무 많이 쪼개진 서비스는 운영에 부담

- 진짜 중복과 가짜 중복
  - 공통 도메인 <mdi-arrow-right-thick /> 공동관리나 어설픈 추상화보다는 조직별 중복 허용

- DB 를 사용하지 않는 경우에 라이브러리화 고민

- 서버간 API 통신 실패 대비 <mdi-arrow-right-thick /> SNS, SQS 비동기 아키텍처 <mdi-arrow-right-thick /> 최종적 일관성 보장

</v-clicks>

---
transition: fade-out
---

# 레거시

레거시 시스템 개편 인프랩 사례

<v-clicks>

- 단일 레거시 시스템의 개편방법
  - Divide & Conquer
  - 레거시를 영역별로 나누어서 각 팀에 할당 (~~육망성 치킨~~)

- N 배의 인프라 <mdi-arrow-right-thick /> IaC(Infrastructure as Code), Pulumi

</v-clicks>

---
layout: quote
transition: fade-out
---

# 마무리

### 성장: 능동적인 루틴

<br>

### 환경: 우리의 업을 이해, 협업방식과 성과 정의

<br>

### 조직: 혁신 조직 구성을 위해 탐구

<br>

### 아키텍처: 비즈니스를 고려한 아키텍처

---
layout: section
---

# 별첨

---

# 함께 성장하기

인프랩의 미래

신규기능: 잔디심기, 사이드 프로젝트, AI 봇 답변, 랠릿(이력서)...

교육 > 채용 > 커뮤니티 통합 <mdi-arrow-right-thick /> '라이프타임'  커리어 플랫폼

--

#### 하나투어는?

하나투어는 여행으로 고객의 시간을 특별하게 만드는 회사

여행보다 더 짧거나 긴 시간도 특별하게 가능

---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 1/6

회사와 커리어에 대해

#### SW
- 품질이 높은 SW 는 기능 변경 비용이 적음 <mdi-arrow-right-thick /> 비직관적
- 변화하는 환경 (지도와 내비게이션) <mdi-arrow-right-thick /> 사전설계만큼 리팩토링 중요
  - TDD 도 변화 <mdi-arrow-right-thick /> Inside-Out, Outside-In

#### 회사와 이직
- 회사: 기여할 것, 배울 것, 미래의 나에게 도움되는 것이 있는가?
- 이직: 리더의 방향성, 할 일, 처우

#### 주니어와 시니어, 뭐가 다를까
- 주니어: 주어진 일을 일정안에
- 시니어: 일의 완결성, 품질, 팀에 도움
- 그 이상: 문화선도, 타직군 의사소통 <mdi-arrow-right-thick /> 스태프 엔지니어

---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 2/6

환경에 대해

#### 업무환경
- '무엇'과 '언제'는 협의사항 <mdi-arrow-right-thick /> 커뮤니케이션을 배워라
- '어떻게' 는 우리의 선택 <mdi-arrow-right-thick /> TDD, 코드리뷰, 리팩토링 해라
  > 전문성을 발휘하는데 허락이 필요한가? - 백명석
- 일정이 촉박해서 리팩토링이 안된다 <mdi-arrow-right-thick /> 시간이 실력이다. 학습으로 실력을 키워라
- 아는만큼 보인다. 경험을 쌓고 다시 책 <mdi-arrow-right-thick /> 새로운 관점 <mdi-arrow-right-thick /> 다시 코드
- 항상 품질이 중요? <mdi-arrow-right-thick /> 품질은 범위, 시간, 비용으로 결정되는 것
- '무엇'을 공부해야 하나 <mdi-arrow-right-thick /> 학습 능력, '어떻게' 잘 배울 수 있나? <mdi-arrow-right-thick /> 습관 Routine

#### 팀원들 동기부여
- 좌절을 준비해라: 스스로 동기부여도 힘들데 다른 사람을?
- 모범이 되어라: 따라하고 싶은 사람
- 하지마라: 호기심이나 경력개발만을 위한 기술 의사결정

---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 3/6

성장에 대해

#### 전문가
- 성장이란 전문가가 되는 것
  - 드라이퍼스 모델 Dreyfus Model
  > 사회인은 전문가여야 한다.
- 워라밸: 많은 시간을 보내는 회사의 시간이 즐거워야 <mdi-arrow-right-thick /> 즐거우려면 잘해야

#### 배우는 방법
- 어려운 기술을 배우는 방법 <mdi-arrow-right-thick /> 쉬운 문제로 배운다
  > 한번 푼 문제를 TDD 로 다시 풀면서 TDD 를 익혀볼 수 있다. - 켄트 벡
- 어려운 문제는? <mdi-arrow-right-thick /> 쉬운 기술로
  > 만약 어떤게 어렵다면 자주해라 - 마틴 파울러
- 고통의 계곡을 견딜 수 있어야
---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 4/6

SW 개발에 대해

#### SW 가치
- 요구사항을 만족하는 '행위'
- 향후 요구사항에 대응하는 '구조'
  > 처음에 동작하게 만들고 그 다음에 좋은 구조를 만들어라 - 켄트벡
- 동작하게 만들고 '반드시' 올바른 구조로 만든다. 그리고 다음 동작을 만든다 <mdi-arrow-right-thick /> 아주 작은 단위로
  - TDD: Red(실패) <mdi-arrow-right-thick /> Green(성공) <mdi-arrow-right-thick /> Blue(리팩토링)

#### 코드리뷰
- 모범을 보여준다 <mdi-arrow-right-thick /> 가독성
- 매몰비용오류 방지: 거절이 가능한 작은 단위로
- 필요한 것만
  - YAGNI: You Ain't Gonna Need it

---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 5/6

일에 대해

#### 신뢰를 쌓는 법
- 시키는 일을 한다 <mdi-arrow-right-thick /> 개선을 건의 <mdi-arrow-right-thick /> 최선의 방법으로

#### 일을 잘 시키는 방법
- 사람(팀)에 일을 할당 <mdi-arrow-right-thick /> 같이 일하게 한다 <mdi-arrow-right-thick /> 몰입과 소통

#### 일을 잘하는 방법
- 기억력? <mdi-arrow-right-thick /> 추적가능성, 검색용이성 <mdi-arrow-right-thick /> 문서화
- 놀래키지 말자 <mdi-arrow-right-thick /> 이슈사항 사전 공유

---

# 지속가능한 소프트웨어 개발을 위한 경험과 통찰 6/6

혁신과 성과

### 혁신
- 혁신은 어디에서 오는가
  - 선택과 집중 <mdi-arrow-right-thick /> 다양한 시도
  - 베스트 <mdi-arrow-right-thick /> 유니크
- 실패할 도전부터 빠르게
- 실패를 줄이기: 작은 성공(베이비 스텝) <mdi-arrow-right-thick /> 최종목표 도달

#### 성과의 평가

- 가장 많은 코드가 가장 큰 성과인가?
  > 당신은 다른 사람의 성공에 어떻게 기여했나요? - 사티아 나델라
- 코드리뷰, 짝프로그래밍 1:1, 몹프로그래밍 1:n

---

# 인프런 아키텍처 2023 - 2024 1/3

조직구조

조직 구조 변화에 따른 아키텍처 개편 전략

회사가 커지지만 비즈니스 속도를 유지하면서 개선 <mdi-arrow-right-thick /> 조직구조 개편

#### Cell 목적조직
- PM, 기획자, 디자이너, 개발자가 한 셀에 <mdi-arrow-right-thick /> 의사결정 속도 <mdi-arrow-up />
- 내부 코드보다 제품 지표 <mdi-arrow-right-thick /> 장기제품 <mdi-arrow-down />
- 시니어, 퇴사자 <mdi-arrow-right-thick /> 조직안정성 <mdi-arrow-down />

#### Part 직군조직
- 파트별 위키
- 정기미팅(장애회고)
- PR

---

# 인프런 아키텍처 2023 - 2024 2/3

레거시와 인프라

### 레거시
- 단일한 레거시 시스템의 개편은 누가? <mdi-arrow-right-thick /> Divide & Conquer
- 레거시를 영역별로 나누어서 각 팀에 할당 (육망성 치킨)

### 인프라
- N 배의 인프라 <mdi-arrow-right-thick /> IaC(Infrastructure as Code), Pulumi
- 각 조직별 서비스를 서브디렉토리로 구분
- Load Balancer 보다 Cloud Front 사용 (WHY?)
- 내부 통신에 외부 DNS 의존 <mdi-arrow-right-thick /> Private Load Balancer 추가
- 서버간 API 통신 실패 대비 <mdi-arrow-right-thick /> SNS, SQS 비동기 아키텍처 <mdi-arrow-right-thick /> 최종적 일관성 보장

---

# 인프런 아키텍처 2023 - 2024 3/3

#### 단일 DB

- N 개의 프로젝트와 1 개의 DB
- DDL 은 단일 채널에 공지
- 조직별 DB 계정

#### 기타 고민

- 공통 도메인은 공동 관리? <mdi-arrow-right-thick /> 어설픈 추상화보다는 조직별 중복을 허용
- 비즈니스 독립적인 기능을 다루는 조직 <mdi-arrow-right-thick /> DevOps
- 인증/권한 <mdi-arrow-right-thick /> API Gateway
- public / private 별 Repo 로 분리하여 구성 예정
> 소프트웨어 구조는 해당 소프트웨어를 개발한 조직의 커뮤니케이션 구조를 닮게 된다. - 콘웨이의 법칙

---

# 절반의 성공, 마이크로 서비스 아키텍처 도입과 조직 구조 1/3

조직 구조에 대한 고민

#### 스포티파이: Mission, Funcion 조직
- Mission(Squad): 제품을 개발하는 조직
- Function(Chapter): 비슷한 기술 조직
- https://hcgheader.cafe24.com/data/editor/2010/34457259b842802a52b6af36ff8be5c1_1602552055_8152.png

목적조직: PM 과 EM 을 중심으로 한 제품팀

#### 목적과 자율
- 높은 목적성과 높은 자율성 <mdi-arrow-right-thick /> 협력적 문화를 가진 혁신 조직
- https://hcgheader.cafe24.com/data/editor/2010/34457259b842802a52b6af36ff8be5c1_1602552122_5922.png

조직구조를 개편: 팀간 종속성 최소화를 위해

---

# 절반의 성공, 마이크로 서비스 아키텍처 도입과 조직 구조 2/3

팀 토폴로지

> https://www.yes24.com/Product/Goods/96362958 - 팀 토폴로지

#### 팀 유형
- Stream-Aligned Team: 낚시를 한다
- Enabling Team: 낚시 방법 고민
- Complicated Subsystem Team: 참치팀
- Platform Team: 낚시 도구 관리/개선

#### 팀간 상호작용
- 협력 Collaboration: 함께 일한다.
- 촉진 Facilitating: 다른 팀을 지원하거나 지원받는다.
- X-as-a-Service: 무엇인가를 제공하거나 소비한다.

---

# 절반의 성공, 마이크로 서비스 아키텍처 도입과 조직 구조 3/3

MSA 도입을 위한 고민

#### 작게만 서비스를 나누지 않는다
- Auth 와 Account, Reward 와 Point 사례
- 너무 많이 쪼개진 서비스는 운영에 부담감

#### 비즈니스 목적에 따라 서비스를 나눈다
- 서비스 경계 <mdi-arrow-right-thick /> 광고와 리워드
- DB 를 사용하지 않는 경우에 라이브러리화 고민
- 진짜 중복과 거짓 중복 (?)

---

# 인프런에서는 수천 개의 테스트코드를 이렇게 다루고 있어요

코드의 동작 <mdi-arrow-right-thick /> 코드의 명세화 <mdi-arrow-right-thick /> 테스트 코드

코드수정 시 버그 <mdi-arrow-right-thick /> 회귀테스트 진행

코드의 복잡성 <mdi-arrow-right-thick /> 테스트를 통해 코드 악취 파악

- 단위: 단일객체
- 통합: 객체간 상호작용
- E2E: 전체 흐름

### 통합테스트에서 객체의 의존성

- 내부 의존: Docker 로 실제 객체를 생성해서 테스트, DB
- 외부 의존: 가짜 객체로 테스트, SMTP

가급적 실제 객체를 사용하고 여의치 않으면 가짜 객체를 사용

---

# 스프링과 함께 더 나은 개발자 되기 1/7

기술을 통한 성장이 가능한가

EJB 시절에 오픈소스로 만들어진 스프링

#### 스프링을 통해 본 기술 선택에 대한 고민 3가지
- 기술의 등장배경
  - EJB 의 대안
  > https://www.wiley.com/en-au/Expert+One+on+One+J2EE+Design+and+Development-p-9780764543852 - 로드 존슨
- 존경하는 개발자의 추천
  > 컨플루언스 개발에 스프링을 활용하고 있는데 좋은거 같다 - 마이크 캐논 브룩스
- 공식문서와 튜토리얼, 소스코드
  - 당시 적은 양의 공식문서, PetClinic, 소스코드의 주석

---

# 스프링과 함께 더 나은 개발자 되기 2/7

스프링의 특징

실전 ERP 프로젝트에 스프링을 적용 <mdi-arrow-right-thick /> 하기로 마음먹었으면 무슨 일이 있어도 한다 <mdi-arrow-right-thick /> 성장의 첫걸음

#### 버그가 없는 스프링, 하지만 다른 고민들
- 이걸 왜 이렇게 개발해야하는거지?
- 이건 도대체 뭐 하는거야?
- 왜 개발이 잘되지?

---

# 스프링과 함께 더 나은 개발자 되기 3/7

스프링은 DI/IoC 컨테이너

#### 스프링의 장점들
- 시간이 지나도 기능이 변해도 코드를 파악하기 어렵지 않음 <mdi-arrow-right-thick /> 생산성이 유지
- 기술에 대한 생각이 사라짐(기술이 의식되지 않음) <mdi-arrow-right-thick /> 도메인에 집중

스프링이 강조하는 DI/IoC 가 도대체 무엇이고, 내 코드에 어떤 영향을 미치나?

#### 서적, 글, 교류를 통한 이해
- 스프링이 추구하는 가치, 철학에 대한 이해
- 스프링의 목표: POJO 를 이용해 복잡한 서비스를 선언적이고 비침투적으로 구현하는 것

#### 구현과 구성의 분리
- 구현: POJO
- 구성: 컨테이너

---

# 스프링과 함께 더 나은 개발자 되기 4/7

DI 와 IoC

DI/IoC 는 객체지향 설계윈칙에 충실하기 위해 나온 것
- DI: 객체내부에서 다른 객체에 대한 의존관계를 외부에서 정의해주는 것
- IoC: 오브젝트 내부에서 하나의 오브젝트가 내가 의존하는 오브젝트에 대한 의존관계를 결정할 수 있는 권한을 자기가 가지지 않고 제3의 오브젝트한테 위임한 것

#### DI/IoC 에 대한 설명
- Inversion of Control Containers and the Dependency Injection pattern
  > https://martinfowler.com/articles/injection.html
- InversionOfControl
  > https://martinfowler.com/bliki/InversionOfControl.html
- IoC: 프레임워크의 특징, 사용자가 기능 생성, 프레임워크가 호출
- DI: 스프링에서 구동되는 특별한 IoC, 스프링에서는 어떤 제어를 역전하는가? <mdi-arrow-right-thick /> 종속성

---

# 스프링과 함께 더 나은 개발자 되기 5/7

Design Pattern, Object-Oriented

#### 디자인 패턴
- DI/IoC 를 구현하는 대표적인 패턴: 전략패턴, 컴포지트 패턴
- POJO 로 구현하고 실행 시 컨테이너를 통해 조합하는 것
- 전략을 쓰면 기존의 코드를 건드리지 않고 기능을 끊임없이 확장할 수 있음

#### 스프링에서의 디자인 패턴
- 디스패처 서블릿은 핸들러와 전략의 모음
- AOP 도 데코레이터, 프록시패턴을 적용한 것

#### 객체지향
- 객체지향 설계란 변화를 대비한 설계, 외부의 변화를 감당하면서 흔들리지 않는 견고한 설계

---

# 스프링과 함께 더 나은 개발자 되기 6/7

#### 질문과 탐구
- 탐구: 스프링의 철학 <mdi-arrow-right-thick /> 스프링의 설계방식 <mdi-arrow-right-thick /> 디자인 패턴과 객체지향 설계

#### 훈련과 개선
- 회사에서 하는 코딩 외의 코딩이 있는가?
  - 튜토리얼 예제 따라하기 (30번)
- 연습용 애플리케이션 

---

# 스프링과 함께 더 나은 개발자 되기 7/7

#### 테스트
- TDD 의 전제
  - 로드존슨의 책에서도 테스트에 대한 자세히 다룸
- 스프링의 소스코드에 있는 테스트 코드
- 학습 테스트
  - 새로운 기술을 배울 때 도움
  - 외부 라이브러리의 버전 변경 시 확인 가능

#### 공유와 논쟁
- 고민을 통해 선택, 내가 한 선택에 대한 이유
- 고민과 경험을 글로
- 나만의 효율적인 정리법 찾기, 검색이 용이하게

---

# 시니어 개발자 너머의 성장 1/4

남상수 스포티파이 

고정마인드셋, 성장마인드셋

70-20-10 학습모델
- 70%: 업무경험
- 20%: 동료 상호작용
- 10%: 공식적 교육

성장에는 개인의 능동적인 노력이 강조

업무의 방향과 성장의 방향의 일치가 중요

---

# 시니어 개발자 너머의 성장 2/4

시니어개발자와 스태프 엔지니어

#### 시니어 개발자: 팀의 성공
- 엔지니어링 관행 개선 및 주도
- 멘토링, 협업, 코드리뷰

시니어개발자 이후 개인기여자(IC) = 스태프 엔지니어

#### 스태프 엔지니어: 조직의 성공
- 엔지니어 성공 사례 교육
- 장기전략
- 기술적 문제 해결
- 조직별로 강조되는 역할이 다르다

---

# 시니어 개발자 너머의 성장 3/4

#### 스태프 엔지니어의 원형 archetype
- 기술리드 Tech Lead
- 아키텍트 Architect
- 해결사 Solver
- 오른손 Right Hand

팀을 넘어 조직에 가치를 제공

https://staffeng.com/guides/staff-archetypes/

#### 왜 조직에 스태프 엔지니어가 필요한가?
- 기술표준화
- 선행연구
- 기술의 전사적 도입

---

# 시니어 개발자 너머의 성장 4/4

#### 기술문제 해결 단계
- 기술문제 식별 및 정의
- 기술제안서 작성 Request For Comments
- 기술방향 결정 Architecture Decision Record

#### 스태프 엔지니어 역할
- Tech Radar: 새로운 기술에 대한 평가 및 적용
- Fleet Management: 서비스간 의존관계 정리
- Sound Check: 품질의 정의 및 관리, 품질측정 자동화, 도구제공(대시보드)

성장이란 새로운 경험 + 익숙하게 되는 여정, 그리고 방향성

개인이 방향성과 조직의 요구사항의 균형

---
layout: end
---

End Of Document