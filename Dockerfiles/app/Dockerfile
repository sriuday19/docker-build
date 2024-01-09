FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
ADD docker-build-test /vprofile-app
RUN cd vprofile-app && mvn install
