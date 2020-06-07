# A Docker image based on Ubuntu with Docker installed

```
docker build --tag jasonmorsley/ubuntu-with-docker .
```

```
docker run -it ubuntu-with-docker ./bin/sh
```

or 

```
winpty docker run -it ubuntu-with-docker ./bin/sh
```

## Push image to Docker Hub

```
docker push jasonmorsley/ubuntu-with-docker
```
