FROM openjdk:8
ADD target/publish-service.jar publish-service.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "publish-service.jar"]