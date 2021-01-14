# Docker TP
## Commands to install the docker
docker build . -f DockerFile -t dockertp

docker run -dp 8002:80 --name DockerTP dockertp

## Commands to manage the docker
docker start DockerTP

docker stop DockerTP

docker restart DockerTP

## Commands for docker-compose
docker-compose up

## URL
### Apache
http://localhost:8002
