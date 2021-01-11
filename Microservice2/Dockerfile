#docker build -t imagename:tagname "location of docker file"
#docker build -t microservice2:1.0 .
#docker save microservice2 > /d/Learning/Microservice2/microservice2
#docker run microservice2:1.0 OR docker run IMAGE_ID
#docker-machine ip
#ADD <source from where Docker should create the image> <destination>
FROM openjdk:8-jdk-alpine
EXPOSE 8081
ADD target/microservice2-0.0.1-SNAPSHOT.jar microservice2-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "microservice2-0.0.1-SNAPSHOT.jar"]