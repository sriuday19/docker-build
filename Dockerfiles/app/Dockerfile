FROM openjdk:11
WORKDIR vprofile-project
RUN apt update -y
COPY /src vprofile-project/src
COPY /pom.xml vprofile-project
RUN cd vprofile-project && ls -l