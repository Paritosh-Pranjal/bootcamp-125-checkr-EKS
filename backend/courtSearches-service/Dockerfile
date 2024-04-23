FROM openjdk:17
WORKDIR /courtSearches-service
COPY target/*.jar app.jar
EXPOSE 9003
ENTRYPOINT [ "java","-jar","app.jar" ]