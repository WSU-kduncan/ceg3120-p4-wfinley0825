# Getting Started with Docker

First thing I did was install Docker through the website provided in the project folder
[Docker](https://www.docker.com/products/docker-desktop)

Next thing is that I created an html folder inside the repository 

After that I created the DockerFile in order to get my html website in the Docker container

Commands that I used to get the DockerFile to run: `docker build nginix .` inside the repo which held my HTML file and the dockerfile 
I also used `docker run -d -p 5000:80 nginix`

I also used this [website](https://hub.docker.com/_/httpd) for help on getting Docker to work

Here is proof of my docker working 

![Docker Proof](DockerProof.PNG)
