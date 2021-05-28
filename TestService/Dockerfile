FROM openjdk:8
ADD target/TestService.jar TestService.jar
EXPOSE 8085
ENTRYPOINT ["java" , "-jar", "TestService.jar"]