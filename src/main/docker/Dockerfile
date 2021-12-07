FROM openjdk
MAINTAINER PepsiGoose <salty.mech.dad@gmail.com>
ADD sample-docker-microservice-1.0-SNAPSHOT.jar person-service.jar
ENTRYPOINT ["java", "-jar", "/person-service.jar"]
EXPOSE 8080