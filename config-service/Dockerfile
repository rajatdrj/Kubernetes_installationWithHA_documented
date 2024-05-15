FROM openjdk
LABEL maintainer="cctns" version="1.0"  description="config-server"
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} psa-config-server-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/psa-config-server-0.0.1-SNAPSHOT.jar"]
EXPOSE 8989