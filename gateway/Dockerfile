FROM openjdk:8-jdk-alpine
MAINTAINER lihongjie

ADD ./target/springclouddemo-gateway.jar /app/
CMD ["java", "-Xmx512m", "-jar", "-Dspring.profiles.active=docker", "/app/springclouddemo-gateway.jar"]

EXPOSE 8702