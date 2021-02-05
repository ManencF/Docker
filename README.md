# Docker TP
## Commands to install the docker
docker build . -f DockerFile -t dockertp

docker run -dp 8002:80 --name DockerTP dockertp

## Commands to manage the docker
docker start DockerTP

docker stop DockerTP

docker restart DockerTP

## Commands for docker-compose
docker-compose build --pull

docker-compose up

docker-compose down

docker-compose down --volumes

## URL
### Traefik
http://localhost:8080

### NextCloud
http://nextcloud.localhost/
