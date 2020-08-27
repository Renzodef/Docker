## BUILD THE IMAGES
- Go with terminal in this folder and type: <br>
docker-compose build

## RUN THE MONGO CONTAINER
- Go with terminal in this folder and type: <br>
docker-compose up -d mongo

## RUN THE APP CONTAINER
- Go with terminal in this folder and type: <br>
docker-compose up -d app <br>
- Then go in the browser at the url: <br>
localhost:4000 

## RUN THE CLIENT CONTAINER
- Go with terminal in this folder and type: <br>
docker-compose up -d client <br>
- Then go in the browser at the url: <br>
localhost:3000 

## STOP ALL CONTAINERS
- Go with terminal in this folder and type: <br>
docker-compose stop
