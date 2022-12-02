FROM openjdk:8
ADD target/request_service_app-0.0.1-snapshot.jar customerrequest-aws-ecs.jar
ENTRYPOINT ["java","-jar","/customerrequest-aws-ecs.jar"]