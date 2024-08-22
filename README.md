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
# docker logs <container ID>
# docker -rm -f $(docker ps -aq)

```
## Docker mysql

```
# $ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag

# $ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=simpl3-paZZw0rd -d mysql:latest

# docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -p3306:3306 -d mysql

# mysql -uroot -h127.0.0.1 -p

