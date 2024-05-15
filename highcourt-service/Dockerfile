FROM docker-registry:5000/openjdk
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-highcourt-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-highcourt-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8887