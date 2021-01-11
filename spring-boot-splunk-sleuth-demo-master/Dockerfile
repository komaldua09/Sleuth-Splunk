#docker build -t imagename:tagname "location of docker file"
#docker build -t spring-boot-sleuth-splunk-demo:1.0 .
#docker save spring-boot-sleuth-splunk-demo > /d/Learning/'spring-boot-splunk-sleuth-demo-master'/'spring-boot-splunk-sleuth-demo-master'/angulardockerimage
#docker run spring-boot-sleuth-splunk-demo:1.0 OR docker run IMAGE_ID
#docker-machine ip
FROM openjdk:8-jdk-alpine
EXPOSE 8080
#ADD <source from where Docker should create the image> <destination>
ADD target/spring-boot-sleuth-splunk-demo-0.0.1-SNAPSHOT.jar spring-boot-sleuth-splunk-demo-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "spring-boot-sleuth-splunk-demo-0.0.1-SNAPSHOT.jar"]