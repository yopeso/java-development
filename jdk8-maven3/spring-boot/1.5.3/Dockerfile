FROM maven:3-jdk-8
MAINTAINER Bogdan Suciu <bogdan.suciu@yopeso.com>

RUN mvn org.apache.maven.plugins:maven-dependency-plugin:2.8:get -Dartifact=org.springframework.boot:spring-boot-starter-web:1.5.3.RELEASE
RUN mvn org.apache.maven.plugins:maven-dependency-plugin:2.8:get -Dartifact=org.springframework.boot:spring-boot-starter-test:1.5.3.RELEASE
RUN mvn org.apache.maven.plugins:maven-dependency-plugin:2.8:get -Dartifact=org.springframework.hateoas:spring-hateoas:0.23.0.RELEASE
