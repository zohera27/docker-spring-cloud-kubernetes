FROM openjdk:8-jdk-alpine
VOLUME /c/Users/azhar27/
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java -jar app.jar --info
