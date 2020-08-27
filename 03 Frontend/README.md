## BUILD THE IMAGES
- Go with terminal in this folder and type: <br>
docker build -t frontend . <br>
(You can change frontend with any name you like)

## RUN THE CONTAINER
- Go with terminal in this folder and type: <br>
docker run -p 3000:3000 frontend <br> 
(Change frontend according to the name you gave when the images were builded) <br>
- Then go in the browser at the url: <br>
localhost:3000 

## STOP THE CONTAINER
- Go with terminal in this folder and type: <br>
docker ps
- Copy the id of the frontend container
- Go with terminal in this folder and type: <br>
docker stop docker_container_id <br>
(Change "docker_container_id" with the id you copied before) 
