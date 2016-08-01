# Hello Single Sign On (SSO) Example with JSON Web Token (JWT), Spring Boot - Authentication Service

## Guide
https://hellokoding.com/hello-single-sign-on-sso-with-json-web-token-jwt-spring-boot/

## What you'll need
- JDK 1.7+
- Maven 3+

## Stack
- Java
- Spring Boot
- FreeMarker

## Run
Find Resource Service [here](https://github.com/hellokoding/hello-sso-jwt-resource)

- Run Authentication Service: `mvn spring-boot:run`
- Run Resource Service 1: `mvn spring-boot:run -Dserver.port=8180`
- Run Resource Service 2: `mvn spring-boot:run -Dserver.port=8280`
