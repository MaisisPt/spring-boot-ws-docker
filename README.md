# spring-boot-ws-docker

Simple Spring Boot Web Service with Docker Example

```
mvn package docker:build

docker stop spring-boot-ws-docker

docker rm spring-boot-ws-docker

docker run --name=spring-boot-ws-docker -p 8080:8080 -t mfamador/spring-boot-ws-docker 

curl http://localhost:8080

curl http://localhost:8080/greeting?name=marco
```