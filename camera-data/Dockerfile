FROM docker-registry:5000/openjdk
LABEL maintainer="cctns" version="1.0"  description="camera-data-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-camera-data-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-camera-data-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 9093