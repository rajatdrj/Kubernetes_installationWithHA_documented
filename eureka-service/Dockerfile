FROM openjdk
LABEL maintainer="cctns" version="1.0"  description="eureka-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-registry-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-registry-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8761