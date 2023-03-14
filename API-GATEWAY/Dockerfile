FROM openjdk:17

EXPOSE 9090

ADD target/cloudgateway.jar cloudgateway.jar

ENTRYPOINT ["java","-jar","cloudgateway.jar"]