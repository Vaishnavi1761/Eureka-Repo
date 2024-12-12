FROM openjdk:17-jdk-alpine
MAINTAINER "vaishnavi"
EXPOSE 7000
COPY ./target/SpringBootPatientService.jar   SpringBootPatientService.jar 
CMD ["java","-jar","SpringBootPatientService.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
#WORKDIR  /usr/local/bin/
