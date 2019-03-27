## Dockerfile Instruction

- To build the docker image, run the following command:
```
docker build .
```
- After the docker build process you have built an image that can run the Node.js app

- To run docker container, run the following command:
```
docker run -p 3000:3000 -it <image id>
```

To see the ```Hello World```, run the following command:
```
curl localhost:3000
```

## Docker Registry

Log in to Docker Cloud using the ```docker login``` command.
```
docker login
```

Tag your image using ```docker tag``` command.
```
docker build -t sayems/demo
```

Push your image to Docker Hub using ```docker push``` command.
```
docker push sayems/demo
```