# otaibe-nginx-with-eureka-demo-eureka-server
Demo project serving to show how to use NGINX with eureka

## Build
From the project dir run the following commands:
```
mvn clean package
docker build -f src/main/docker/Dockerfile.jvm -t triphon/otaibe-nginx-with-eureka-demo-eureka-server .
```

## Run
From the project dir run the following command:
```
docker run -i --rm -p 24455:24455 triphon/otaibe-nginx-with-eureka-demo-eureka-server
```
