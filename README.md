### Docker commands 

docker ps - show running containers

### Dcokerfile first example

vim Dockerfile

FROM ubuntu:16.04 

RUN apt-get update

### List Docker CLI commands

`docker

`docker container --help`

### Display Docker version and info
`docker version`

`docker info`

### Execute Docker image
`docker run hello-world`

### List Docker images
`docker image ls`

### List Docker containers (running, all, all in quiet mode)
`docker container ls`

`docker container ls --all`

`docker container ls -aq`