FROM openjdk:17-jdk-alpine
MAINTAINER "Ashu"
EXPOSE 7000
COPY ./target/1a-eurekaServer-0.0.1-SNAPSHOT.jar   1a-eurekaServer-0.0.1-SNAPSHOT.jar.jar 
CMD ["java","-jar","1a-eurekaServer-0.0.1-SNAPSHOT.jar.jar"]
 
#CMD ["java","-Dspring.profiles.active="development", "-jar","product.war"]
#WORKDIR  /usr/local/bin/