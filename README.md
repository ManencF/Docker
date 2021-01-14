# Docker TP
# Commands to start the docker
docker build . -f DockerFile -t DockerTP
docker run -dp 8002:80 DockerTP
