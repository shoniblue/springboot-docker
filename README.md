# springboot-docker
Simple hello world app using Spring Boot and Docker

```
$ mvn clean package docker:build

//for 'Docker for mac'
$ docker run --name demo -p 8080:1849 sblue/demo

//for linux
$ docker run --name demo -p 1849:1849 sblue/demo
```
