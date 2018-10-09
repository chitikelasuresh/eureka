FROM openjdk:10-jre-slim
COPY target/eureka-service-0.0.1-SNAPSHOT.jar /usr/src/hola/
WORKDIR /usr/src/hola
EXPOSE 8070
CMD ["java", "-jar", "eureka-service-0.0.1-SNAPSHOT.jar"]



