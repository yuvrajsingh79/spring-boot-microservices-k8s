FROM openjdk:8
ADD /publish-service/target/publish-service.jar publish-service.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "publish-service.jar"]