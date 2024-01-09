FROM openjdk:11 AS BUILD_IMAGE
RUN apt update && apt install maven -y
<<<<<<< HEAD
COPY .././ vprofile-app
=======
ADD .././ vprofile-app
>>>>>>> b6e64ed4692ab7cc9d5bfe7216137caa26b5a896
RUN cd vprofile-app && mvn install
