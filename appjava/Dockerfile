# FROM openjdk:8-jdk-slim
FROM openjdk:8
WORKDIR /app
ARG JAR_FILE=springapp.jar
COPY $JAR_FILE .
EXPOSE 8080

ENV EXECUTAVEL=$JAR_FILE
ENV STAGE=desenvolvimento
ENTRYPOINT java -jar $EXECUTAVEL
