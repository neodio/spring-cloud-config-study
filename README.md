# Spring Cloud gateway 학습
Spring Cloud로 개발하는 마이크로서비스 애플리케이션(MSA)
강의 학습 내용 설정파일 자료
https://inf.run/4n2P6

## 메인 프로젝트 저장소
https://github.com/neodio/spring-cloud-study

## 프로젝트별 설명

| 프로젝트                       | 설명                     | 포트    | 비고                        |
|----------------------------|--------------------------|---------|-----------------------------|
| gateway-first-service      | first-service            | 8081    |                             |
| gateway-second-service     | second-service           | 8082    |                             |
| spring-cloud-gateway       | 게이트웨이(메인)         | 8000    |                             |
| spring-cloud-eureka        | 유레카 서버              | 8761    |                             |
| spring-cloud-eureka-client | 유레카 클라이어트 예제   | 0(랜덤) |                             |
| spring-cloud-zuul-service  | netflix zuul 예제        | 8000    | deprecated로 gateway로 대체 |
