FROM openjdk:8-jdk-alpine
MAINTAINER lihongjie

ADD ./target/springcloud-demo-admin.jar /app/
CMD ["java", "-Xmx512m", "-jar", "-Dspring.profiles.active=docker", "/app/springcloud-demo-admin.jar"]

EXPOSE 8703