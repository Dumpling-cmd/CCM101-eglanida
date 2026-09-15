# Docker Deployment

## Docker Environment Verification

### Check Docker Version

```bash
docker --version
```

This command displays the installed Docker version.

### Check Docker Information

```bash
docker info
```

This command displays detailed information about the Docker environment and Docker daemon.

## Deploying Nginx

### Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

### Run the Nginx Container

```bash
docker run -d -p 8080:80 --name nginx-server nginx
```

This command creates and starts an Nginx container in detached mode and maps host port 8080 to port 80 inside the container.

### Test the Web Server

```bash
curl http://localhost:8080
```

This command sends an HTTP request to the Nginx web server through port 8080 and verifies that the server is responding.

## Container Lifecycle

### List Running Containers

```bash
docker ps
```

This command lists the containers that are currently running.

### Stop the Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container.

### Verify the Container Is Stopped

```bash
docker ps -a
```

This command displays running and stopped containers so the status of the Nginx container can be verified.

### Remove the Container

```bash
docker rm nginx-server
```

This command permanently removes the stopped Nginx container.

### Verify Removal

```bash
docker ps -a
```

This command verifies that the `nginx-server` container has been removed.
