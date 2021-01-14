# Docker TP
## Commands to start the docker
docker build . -f DockerFile -t dockertp

docker run -dp 8002:80 --name DockerTP dockertp

docker stop DockerTP

## docker-compose
docker-compose up

## URL
### Apache
http://localhost:8002
