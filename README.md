# Project Overview

## Run Project Locally

First thing I did was install Docker through the website provided in the project folder
[Docker](https://www.docker.com/products/docker-desktop)

Next thing is that I created an html folder inside the repository 

After that I created the DockerFile in order to get my html website in the Docker container

Commands that I used to get the DockerFile to work correctly were: `docker build nginix .` to build the container, and `docker run -d -p 5000:80 nginix` to run the container.

The address to get the the website to show up is the website followed by a colon and the port, which is 

I also used this [website](https://hub.docker.com/_/httpd) for help on getting Docker to work

Here is proof of my docker working 

![Docker Proof](DockerProof.PNG)
