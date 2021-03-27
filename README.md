# 교육 설명
[교육과정 보기](https://edu.nextstep.camp/c/lqsBs7x0/)
* NextStep & 우아한 형제들 주관
* 일반 사용자용 서비스를 개발할 때 필요한 역량 습득
* 리뷰어의 코드 리뷰를 통해 책임 주도 설계를 기반으로 유연한 구조의 클린 코드를 작성

## 배운 점

### 미션 주요 내용
ATDD(Acceptance test - 인수테스트)의 정의, 사용시 이점을 활용하여 구현
* ATDD 시나리오(사용자 스토리) 테스트
  * 팀원과의 협업을 도와주는 애자일 중 하나 (팀원들의 공통적인 이해를 도움)
  * TDD의 단점을 보완하고, TDD를 시나리오 테스팅 영역까지 확장한 것
  * 도메인과 시나리오에 대한 이해도 증진

### Step 1
**[Step1 피드백 보기](https://github.com/next-step/atdd-subway-admin/pull/22)**

**주요 피드백 내용**
* 요청 테스트에서 필요한 파라미터는 해당 요청에서 생성하여 사용하는 것이 간결함
* 협업하는 팀원을 위해 테스트 코드 사용법이 쉬워야 함
* 요청 테스트 수행 시 가독성을 위해 요청 파라미터 타입(규격) 통일

### Step 2
**[Step2 피드백 보기](https://github.com/next-step/atdd-subway-admin/pull/43)**

**주요 피드백 내용**
* 도메인 용어를 통일해 사용할 것
* 직관적인 코드를 위해 정적 팩터리 메서드명을 명명 시 구조에 맞는 컨벤션 적용
  * 예를 들어 from은 하나의 인자를 받아 인스턴스 생성, of는 여러 인자를 받아 인스턴스 생성 시에 사용

### Step 3
[Step3 피드백 보기](https://github.com/next-step/atdd-subway-admin/pull/58)

**주요 피드백 내용**
* 정적 팩터리 메서드에서 다른 인스턴스 생성 시 `createInstance()` 등으로 명명하여 직관적으로 작성할 것
* 의미 없는 검증문(`assert`)을 꼼꼼히 확인하여 문맥에 맞는 검증문을 작성할 것
* 기능과 검증 처리 로직을 분리하여 책임 분할하여 유연하고 직관적인 코드를 작성할 것 
* 람다는 길어지면 가독성이 떨어질 수 있기 때문에 메서드 참조 등으로 변환할 것

### Step 4
[Step4 피드백 보기](https://github.com/next-step/atdd-subway-admin/pull/63)

**주요 피드백 내용**
* 피드백 내용 없음

---

<p align="center">
    <img width="200px;" src="https://raw.githubusercontent.com/woowacourse/atdd-subway-admin-frontend/master/images/main_logo.png"/>
</p>
<p align="center">
  <img alt="npm" src="https://img.shields.io/badge/npm-%3E%3D%205.5.0-blue">
  <img alt="node" src="https://img.shields.io/badge/node-%3E%3D%209.3.0-blue">
  <a href="https://edu.nextstep.camp/c/R89PYi5H" alt="nextstep atdd">
    <img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fedu.nextstep.camp%2Fc%2FR89PYi5H">
  </a>
  <img alt="GitHub" src="https://img.shields.io/github/license/next-step/atdd-subway-admin">
</p>

<br>

# 지하철 노선도 미션
[ATDD 강의](https://edu.nextstep.camp/c/R89PYi5H) 실습을 위한 지하철 노선도 애플리케이션

<br>

## 🚀 Getting Started

### Install
#### npm 설치
```
cd frontend
npm install
```
> `frontend` 디렉토리에서 수행해야 합니다.

### Usage
#### webpack server 구동
```
npm run dev
```
#### application 구동
```
./gradlew bootRun
```
<br>

## ✏️ Code Review Process
[텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

<br>

## 🐞 Bug Report

버그를 발견한다면, [Issues](https://github.com/next-step/atdd-subway-admin/issues) 에 등록해주세요 :)

<br>

## 📝 License

This project is [MIT](https://github.com/next-step/atdd-subway-admin/blob/master/LICENSE.md) licensed.
