#docker build -t imagename:tagname "location of docker file"
#docker build -t microservice1:1.0 .
#docker save microservice1 > /d/Learning/Microservice1/microservice1
#docker run microservice1:1.0 OR docker run IMAGE_ID
#docker-machine ip
#ADD <source from where Docker should create the image> <destination>
FROM openjdk:8-jdk-alpine
EXPOSE 8080
ADD target/microservice1-0.0.1-SNAPSHOT.jar microservice1-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "microservice1-0.0.1-SNAPSHOT.jar"]