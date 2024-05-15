FROM docker-registry:5000/openjdk
LABEL maintainer="cctns" version="1.0"  description="report-data-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-reporting-data-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-reporting-data-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 9096
