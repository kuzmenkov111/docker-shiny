shiny
=====

shiny server: 1.2.2.367

Dockerfile to be use to build image for docker container with ubuntu 14.04 plus sshd service and Shiny-server

Shiny server : use to host and manage shiny application (R - powered web application)

To make it work :

docker run -d -p 3838 quantumobject/shiny

You can check http://rstudio.github.io/shiny-server/latest/#configuration-settings for more info about shiny-server

note : it was created by using quantumobject/docker-baseimage and installing the package R and Shiny-server from rstudio.com . RStudio is a trademark of RStudio, Inc.
