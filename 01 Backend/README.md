## BUILD THE IMAGES
- Go with terminal in this folder and type: <br>
docker build -t firstcontainer . <br>
(You can change firstcontainer with any name you like)

## RUN THE CONTAINER
- Go with terminal in this folder and type: <br>
docker run -p 4000:4000 firstcontainer
<br> (Change firstcontainer according to the name you gave when the images were builded) <br>
- Then go in the browser at the url: <br>
localhost:4000 

## OTHER COMMANDS
- See all the docker images: <br>
docker images 
- Remove an image: <br> 
docker rmi "docker_image_id" <br>
(Change "docker_image_id" with the id of the image that you can find after you type docker images)
- See all container running at the moment: <br>
docker ps
- Stop a container that is running: <br>
docker stop "docker_container_id" <br>
(Change "docker_container_id" with the id of the container that you can find after you type docker ps) <br>
- Start a container: <br>
docker start "docker_container_id" 
