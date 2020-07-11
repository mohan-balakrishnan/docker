# Docker Commands

# Remove Docker Images

List:

$ docker images -a

Remove:

$ docker rmi -f $(docker images -a -q)

$ docker images purge

# Remove Docker Containers

List:

$ docker ps -a

Remove:

$ docker stop $(docker ps -a -q)

$ docker rm $(docker ps -a -q)
