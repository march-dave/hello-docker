
## Use docker composer 
## docker compose build
docker-compose up --build

## docker compose stop
docker-compose stop


## Use Docker
## Docker iamge create
docker build -t hello-world-image .

## Docker container running port number from Host OS 8082 to container 8081
docker run -p 8082:8081 hello-world-image

docker run -it --name hello-container -p 8082:8081 hello-world-image /bin/bash
