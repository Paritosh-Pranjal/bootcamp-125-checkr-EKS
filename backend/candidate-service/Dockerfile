FROM openjdk:17
WORKDIR /candidate-service
COPY target/*.jar app.jar
EXPOSE 9002
ENTRYPOINT [ "java","-jar","app.jar" ]