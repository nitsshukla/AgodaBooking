# Getting Started
## Installation
Make sure you have a docker, gradle 6.8+ installed with you.

* Start docker
* Go to the directory and execute the following command:
    * `./gradlew clean build`
    * Fille USER_NAME: `docker image build -t  <USER_NAME>/agoda/booking .` 
    * `docker-compose up`
*  If you don't have docker, you can just run the following command with **CSV** mode:
    *  `./gradlew bootRun -Pargs=--mode=CSV`

##Documentation
*  Refer swagger: http://localhost:8090/swagger-ui/#/booking-controller
*  For monitoring, prometheus is setup at: http://localhost:9090/
*  Actuator endpoints: http://localhost:8090/actuator
  
### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.5.3/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.5.3/gradle-plugin/reference/html/#build-image)
* [Prometheus](https://docs.spring.io/spring-boot/docs/2.5.3/reference/html/production-ready-features.html#production-ready-metrics-export-prometheus)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/2.5.3/reference/htmlsingle/#boot-features-jpa-and-spring-data)
* [Spring Security](https://docs.spring.io/spring-boot/docs/2.5.3/reference/htmlsingle/#boot-features-security)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.5.3/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides
The following guides illustrate how to use some features concretely:

* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

### Additional Links
These additional references should also help you:

* [Gradle Build Scans – insights for your project's build](https://scans.gradle.com#gradle)

