FROM openjdk:latest
LABEL maintainer="cctns" version="1.0"  description="law-order-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-law-order-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-law-order-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 9097