
# Docker-Command
about all commands of Docker 

Docker-desktop : Windows
Docker : Linux



Basic Commands of Docker :-

docker pull Image_name
docker images
docker run  Image_name
docker run -it Image_name
docker start CONT_NAME or CONT_ID
docker stop CONT_NAME or CONT_Id

docker ps ( shows running container )
docker ps -a 
docker rmi IMAGE_NAME (removes images)
docker rm CONT_NAME (removes container) First we have to delete container then the images are able to delete

TroubleShoot Commands :-

docker logs CONT ID
docker exec -it CONT_ID /bin/bash
docker exec -it CONT_ID /bin/sh


For Dockerizing our app :-

FROM
WORKDIR
COPY 
RUN
CMD
EXPOSE
ENV


Docker Compose :-

Docker compose is a tool for defining and running Multi-container applications.
