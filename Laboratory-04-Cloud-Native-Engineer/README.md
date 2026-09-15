# Laboratory 04 – Cloud-Native Engineer

## Mission Overview

This laboratory activity introduces containerization and Docker. The activity compares traditional Virtual Machines with containers and demonstrates how Docker can be used to deploy and manage a containerized Nginx web server.

## Objectives

* Differentiate between Virtual Machines and Containers.
* Access a Docker-enabled cloud environment using KillerCoda.
* Execute fundamental Docker CLI commands.
* Pull, run, manage, and terminate an Nginx container.
* Document Docker container operations using Markdown.

## Docker Commands Executed

```bash
docker --version
docker info
docker pull nginx
docker run -d -p 8080:80 --name nginx-server nginx
curl http://localhost:8080
docker ps
docker stop nginx-server
docker ps -a
docker rm nginx-server
docker ps -a
```

## Skills Learned

Through this activity, I learned how to verify a Docker environment, download Docker images, create and run containers, map network ports, test a containerized web server, and manage the container lifecycle.

## Challenges Encountered

One challenge was understanding how host ports and container ports work together. I also needed to carefully follow the Docker commands in the correct order when running, stopping, and removing the Nginx container. Taking screenshots of the terminal output also helped me verify that each step was completed successfully.
