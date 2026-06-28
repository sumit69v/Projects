### Part I : images and containers

We've defined Docker images and containers and seen how to run simple commands in a Docker container and list all our images and containers.

Here's a list of Docker commands used so far:

how to: | command
------------ | -------------
check Docker version | `docker -v`
download the Linux Alpine image | `docker pull alpine`  
run a simple echo command  |  `docker container run alpine echo 'Hello World!'`
view the message-of-the-day in alpine  |  `docker container run alpine cat /etc/motd`
print 'Hello World!' in Linux Centos (image is downloaded if not present) | `docker container run centos echo 'Hello World!'` 
show all locally available images  |  `docker images`
list Docker containers  |  `docker container ls` (also: `docker ps`)   
view all Docker containers (running or not)  |  `docker container ls -a` (also: `docker ps -a`)   
view all Docker containers (running or not)	docker container ls -a (also: docker ps -a)


### Part II : running containers

We've seen how to: start a container in detached mode, keep a container alive, enter and exit a container, run a command in a running container, stop a container, remove a container.

how to: | command
------------ | -------------
start a container in the background | `docker container run -d alpine ping host.docker.internal`
run a container in the background and keep it alive  |  `docker container run -di alpine`
stop a running container  |  `docker stop container_name_or_id`
execute the command `uname -a` in a running Docker container  |  `docker exec -it container_name_or_id uname -a`
start a shell inside a running container  |  `docker exec -it container_name /bin/sh`
delete a container  |  `docker container rm container_name_or_id`
force-delete a running  container  |  `docker container rm -f container_name_or_id`   
remove an image  |  `docker rmi centos`
force-remove an image  |  `docker rmi -f centos`
