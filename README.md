# jenkins-docker-image

Build image:

` docker build  -t jenkins-container .`

To run 

`docker run -d -p  8080:8080 jenkins-container`

To view images

`docker images`

To access docker container

`docker exec -it <mycontainer> bash`
