FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
COPY docker-build-test vprofile
RUN cd vprofile && ls -l
