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


> study by inflearn 1.0 Release (2023.01.01)