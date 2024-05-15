FROM docker-registry:5000/openjdk
LABEL maintainer="cctns" version="1.0"  description="lost-article-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-lost-article-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-lost-article-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8087