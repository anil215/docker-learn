# docker-learn
Short repo to explore devops 

## Brief description of the folders

## sample-start
Building an image from Dockerfile. Main motive was to get accustomed to using docker commands.

## simple-web
Building a custom image of a sample node app from Dockerfile. Got to learn about using docker cache to speed up the build
process since the relative order of statemnets in the Dockerfile affects it.

## visits
A sample project which uses 2 containers , one to host my custom node app and the other host a redis server. Used 
docker-compose for it. The count is stored in redis and displayed to the client using the node app which communicates
to the redis server. A port if mapped from the node container to a port on machine so that the browser can access it.

## frontend
A sample project which hosts a simple react app inside a docker container. Used references for tracking changes made to the
src directory. The `commands.txt` contains the exact docker commands to run and `docker-compose.yml` file contains how we
simplify the complete process of remembering those heavy commands ;).

