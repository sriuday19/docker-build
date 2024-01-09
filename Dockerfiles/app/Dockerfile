FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
WORKDIR /vprofile
ADD ../../ /vprofile
RUN ls
RUN cd vprofile && mvn install
