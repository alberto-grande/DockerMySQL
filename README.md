# DockerMySQL

Simple repo for a fast MySQL server start

Usefull docker commands: 

docker build -t mpdb

docker run --name mpdb -v "$PWD":/mnt -e MYSQL_ROOT_PASSWORD="passwd" -d mpdb

docker logs mpdb 

docker exec -it mpdb /bin/bash

mysql -uroot -ppasswd
