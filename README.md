# Spring Batch Example Project


## MYSQL DOCKER - Instructions

```
docker pull mysql/mysql-server:latest

docker run -d -p 3306:3306 --name mysql-docker-container -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_DATABASE=spring_batch -e MYSQL_USER=user -e MYSQL_PASSWORD=123456 mysql/mysql-server:latest

sudo docker exec -it mysql-docker-container bash

mysql -u root -p
or
mysql -u user -p
Password: 123456

show databases;
use spring_batch;
show tables;
```
