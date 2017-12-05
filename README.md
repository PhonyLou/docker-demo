# docker-demo
This repo is to store the demos for each applications with docker

### build docker image
mvn install dockerfile:build

### run docker image
docker run -p 8686:8081 -t springio/gs-spring-boot-demo
