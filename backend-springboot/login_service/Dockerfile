FROM openjdk:8
ADD target/login_service_jwt_app-0.0.1-snapshot.jar customerlogin-aws-ecs.jar
ENTRYPOINT ["java","-jar","/customerlogin-aws-ecs.jar"]