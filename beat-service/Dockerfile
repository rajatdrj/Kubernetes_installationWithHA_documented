FROM docker-registry:5000/openjdk
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-beat-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-beat-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8880