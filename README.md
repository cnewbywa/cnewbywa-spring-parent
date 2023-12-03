# Parent Maven project for Spring Boot applications
This project contains a [Maven](https://maven.apache.org/) project that can be used as a parent project for [Spring Boot](https://spring.io/projects/spring-boot) based projects.

## Overview
The project contains the following:

* Dependencies like
    * Spring Boot parent
    * [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)
    * [Lombok](https://projectlombok.org/)
    * [Testcontainers](https://testcontainers.com/)
    * See pom.xml for full list
* Code coverage using [Jacoco](https://www.eclemma.org/jacoco/)
* Separate source directories for [Surefire](https://maven.apache.org/surefire/maven-surefire-plugin) and [Failsafe](https://maven.apache.org/surefire/maven-failsafe-plugin/) tests

## Installation
```
./mvnw clean install
```
