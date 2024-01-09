FROM openjdk:11
RUN apt update -y
COPY ../../src vprofile-project
COPY ../../pom.xml vprofile-project
RUN cd vprofile-project && ls -l