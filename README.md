## cloud_native02

cloud native for docker

## Build the image
```
#  docker build -t anodeapp-demo:1 .
docker build -t <imagename>:<tag> .
```

## Run the image
```
# docker run -p8080:8080 anodeapp-demo:1 
docker run -p<hPort:cPort> <inmagename>:<tag>
```

## Check docker running

```
# docker ps
```
## Stopping docker

```
# docker stop <container ID>
```
## Docker pull

```
# docker pull node:22-alpine
# docker pull node:22 
# docker pull node:22-slim
```
## Check docker images

```
# docker image ls
```
