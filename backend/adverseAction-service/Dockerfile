FROM openjdk:17
WORKDIR /adverseAction-service
COPY target/*.jar app.jar
EXPOSE 9004
ENTRYPOINT [ "java","-jar","app.jar" ]