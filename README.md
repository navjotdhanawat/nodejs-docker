# nodejs-docker
Simple nodejs application with docker

Docker commands:
```
To run docker
$ docker run -p 49160:8080 -d <your username>/node-web-app

This command will list the images which are currently running
$ docker ps

This command will inspect the logs inside the docker image.
$ docker logs <container id>

This command will connect to docker image, just like ssh.
$ docker exec -it <container id> /bin/bash
```