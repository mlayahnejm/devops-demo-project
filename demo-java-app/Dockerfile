# Base image 
FROM openjdk:27-ea-nanoserver-ltsc2025 
#17-ea-17-jdk-slim

# setting artifact path
ARG artifact=target/demo-java-app.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# Entrypoint for running app
ENTRYPOINT ["java","-jar","app.jar"]
