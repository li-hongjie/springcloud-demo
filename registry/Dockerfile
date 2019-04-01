FROM openjdk:8-jdk-alpine
MAINTAINER lihongjie

ADD ./target/springcloud-demo-registry.jar /app/
CMD ["java", "-Xmx512m", "-jar", "-Dspring.profiles.active=docker", "/app/springcloud-demo-registry.jar"]

EXPOSE 8701