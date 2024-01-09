FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
WORKDIR /vprofile-app
COPY ../../ /vprofile-app
RUN mvn install 
