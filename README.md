# tomcat


In this repository contains the installation of Tomcat 10 with JDK 17 using docker-compose.

Install docker and docker-compose on server

If you want to change the version of tomcat or JDK you can change the same on the image.

Create a folder tomcat_data this folder is used to data directory of tomcat app in your server, and sync with container data directory.

The webapps (docroot) specified in volume

To run the service use the command "docker-compose up -d"

Check container status with "docker ps"
