#using OpenJDK 17 as base image
FROM openjdk

#creating new app directory for application files
RUN mkdir /app

#copying application file from host machine to image file system
COPY out/production/HelloWorldDocker/ /app

#setting directory to execute future commands
WORKDIR /app

#run Main class
CMD java Main