FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
ADD . vprofile
RUN cd vprofile && ls -l
