## Dockerfile Instruction

- To build the docker image, run the following command:
```
docker build -t sayems/simpleweb .
```
- After the docker build process you have built an image that can run the Node.js app

- To run docker container, run the following command:
```
docker run -p 8080:8080 sayems/simpleweb
```

Now open a browser and navigate to [http://localhost:8080/](http://localhost:8080/) to see the result.


## Docker Registry

This section will show how to push your images to Docker Hub


Log in to Docker Cloud using the ```docker login``` command.
```
docker login
```

Tag your image using ```docker tag``` command.
```
docker build -t sayems/simpleweb
```

Push your image to Docker Hub using ```docker push``` command.
```
docker push sayems/simpleweb
```