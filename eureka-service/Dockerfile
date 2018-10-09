FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/core-0.1.0-RELEASE.jar target/eureka-service-0.0.1-SNAPSHOT.jar
RUN bash -c 'touch target/eureka-service-0.0.1-SNAPSHOT.jar'
ENTRYPOINT ["java","-jar","-Dspring.profiles.active=local","target/eureka-service-0.0.1-SNAPSHOT.jar"]



