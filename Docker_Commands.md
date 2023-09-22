# Docker Commands

## Remove Docker Images

List:

`$ docker images -a`

Remove:

`$ docker rmi -f $(docker images -a -q)`

`$ docker images purge`

## Remove Docker Containers

List:

`$ docker ps -a`

Remove:

`$ docker stop $(docker ps -a -q)`

`$ docker rm $(docker ps -a -q)`

## Docker Volume:  (-v)

`docker volume`  //get information

`docker volume create`

`docker volume ls`

`docker volume inspect`

`docker volume rm`

`docker volume prune`

Docker image : `docker pull httpd:2.4`

run image as container: `sudo docker run -dit --name myapacheapp -p 8080:80 -v /usr/demo/:/usr/local/apache2/htdocs/ httpd:2.4`
