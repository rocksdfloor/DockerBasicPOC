FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
ADD target/gs-spring-boot-docker-0.0.1-SNAPSHOT.jar gs-spring-boot-docker-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","gs-spring-boot-docker-0.0.1-SNAPSHOT.jar"]