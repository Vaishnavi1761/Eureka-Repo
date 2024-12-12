FROM openjdk:17-jdk-alpine
MAINTAINER "vaishnavi"
EXPOSE 7000
COPY ./target/SpringBootEurekaService.jar   SpringBootEurekaService.jar 
CMD ["java","-jar","SpringBootEurekaService.jar"]

#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
#WORKDIR  /usr/local/bin/
