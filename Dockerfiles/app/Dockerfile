FROM openjdk:11
RUN apt update -y && install maven -y
ADD /../../ vprofile-project
RUN cd vprofile-project && mvn install