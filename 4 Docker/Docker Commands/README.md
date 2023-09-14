Introduction
Docker Commands

docker run - Run a command in a new container
$ docker run ubuntu:18.04 echo "Hello from Ubuntu"
Hello from Ubuntu
    
docker start - Start one or more stopped containers
$ docker start my_container
    
docker stop - Stop one or more running containers
$ docker stop my_container
    
docker build - Build an image from a Dockerfile
$ docker build -t my_image .
    
docker pull - Pull an image or a repository from a registry
$ docker pull ubuntu:18.04
    
docker push - Push an image or a repository to a registry
$ docker push my_image
    
docker exec - Run a command in a running container
$ docker exec my_container ls /
    
docker export - Export a container's filesystem as a tar archive
$ docker export my_container > my_container.tar
    
docker import - Import the contents of a tar archive as a filesystem image
$ docker import my_image.tar my_image
    
docker login - Log in to a registry
$ docker login
    
docker logout - Log out from a registry
$ docker logout
    
docker logs - Fetch the logs of a container
$ docker logs my_container
    
docker ps - List containers
$ docker ps
    
docker inspect - Inspect information about a container or image
$ docker inspect my_container
    
docker stats - Display a live stream of container(s) resource usage statistics
$ docker stats my_container
    
docker top - Display the running processes of a container
$ docker top my_container
    