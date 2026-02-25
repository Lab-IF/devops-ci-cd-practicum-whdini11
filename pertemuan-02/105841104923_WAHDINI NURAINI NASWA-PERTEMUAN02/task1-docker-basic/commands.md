\# Task 1 - Docker Basic Commands



docker pull nginx:alpine

docker run -d --name web-praktikum -p 8080:80 nginx:alpine

docker ps

docker logs web-praktikum

docker exec -it web-praktikum sh

docker stop web-praktikum

docker rm web-praktikum

