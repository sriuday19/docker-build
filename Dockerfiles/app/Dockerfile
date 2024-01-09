FROM openjdk:11
RUN apt update && apt install maven -y
RUN git clone https://github.com/sriuday19/vprofile-ci.git
RUN cd vprofile-ci && mvn install