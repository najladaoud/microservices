FROM openjdk:8
EXPOSE 8762
ADD /target/gateway-0.0.1-SNAPSHOT.jar docker-zuul-gateway.jar
ENTRYPOINT ["java", "-jar", "docker-zuul-gateway.jar"]
