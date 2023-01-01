### Spring

- 스프링은 톰캣을 내장하고 있다.
- 이전에는 웹서버(was)를 직접 서버에 설치를 해놨었다.(톰캣)
- 소스 라이브러리에서 웹서버를 소장하고 있다. 임베디드(내장)
- 실행만해도 웹서버를 띄울 수 있다.(요즘에는~ localhost:8080)
- 라이브러리 하나 빌드하면 끝날 작업

### 스프링부트 라이브러리
- spring boot-starter-web
  - spring-boot-starter-tomcat : 톰캣(웹서버)
  - spring-webmvc : 스프링 웹 mvc

- spring-boot-starter-thymeleaf : 타임리프 템플릿 엔진(View, html)

- spring-boot-starter(공통) : 스프링부트 + 스프링코어 + 로깅
  - spring-boot
    - spring-core
  - spring-boot-starter-loggin
    - logback, slf4j
    
### 테스트 라이브러리
- spring-boot-starter-test

### Spring 'Model'

### Gradle Build
- terminal - gradle 경로 찾기 - ./gradlew build
- 오류 발생 시 ./gradlew clean build -> build 지우고 새로 빌드

### 터미널 서버실행 종료
control + C

### MVC
- model, view, controller

### 인텔리제이
- command +shift + enter = 문장 완성 (); 해 
- control + T = 리팩토링 관련 기능
- command + option + M = 메소드 뽑기

### getter & setter
- 자바 빈 규약
- private 객체 -> 접근하기 위해선 게터 세터

### @ResponseBody
- HTTP의 BODY에 문자 내용을 직접 반환
- viewResolver 대신 'HttpMessageConverter' 동작
- 기본 문자처리 : StringHttpMessageConverter
- 기본 객체처리 : MappingJacson2HttpMessageConverter
- byte 처리 등 기타 여러 HttpMessageConverter가 기본으로 등록되있음

### Optional
- java8에 들어간 기능
- NEP(NullPointException)을 방지할 수 있게 해준다.
- null이 올 수 있는 값을 감싸는 Wrapper클래스로 NPE가 발생하지 않도록 해준다.

### 비교(equals)
- org.assertj.core.api.Assertions;
- Assertions.assertThat(비교값1).isEqualTo(비교값2);

