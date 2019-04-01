FROM openjdk:8-jdk-alpine
MAINTAINER lihongjie

ADD ./target/springcloud-demo-config.jar /app/
CMD ["java", "-Xmx512m", "-jar", "-Dspring.profiles.active=docker", "/app/springcloud-demo-config.jar"]

EXPOSE 8700