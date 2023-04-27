### Dockerfile

Dockerfile is a declarative way of of creating our own images.Docker will give aus some syntax to create our own images.

File name should Dockerfile.

### How to build image from Dockerfile

```
docker build -t[docker-hub-url]/[your-username]/[image-name]:version .
``` 

### How to push image to Dockerhub

```

docker push username/imagename:version
