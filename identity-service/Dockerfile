FROM docker-registry:5000/openjdk
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-identity-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-identity-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 9696