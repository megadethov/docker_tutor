# docker_tutor
<hr>

Get docker help
````
docker
````
````
docker <COMMAND> --help
docker run --help
````
Pull docker image from dockerhub
````
docker pull <DOCKER_HUB_LOGIN>/<IMAGE_NAME>:<TAG>
docker pull megadethov/test-image:latest
````
Run container
````
docker run -p <OUT_PORT>:<IN_PORT> --name <CONTAINER_NAME> -d <IMAGE>
docker run -p 7777:8080 --name my-app -d megadethov/test-image:latest
````
Stop container
````
docker stop <CONTAINER_ID>
````
List of containers
````
docker ps -a
````
List of images
````
docker images
````
Remove container
````
docker rm <CONTAINER_ID>
docker rm <CONTAINER_NAME>
````

