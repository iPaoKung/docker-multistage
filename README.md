# docker-multistage
### docker build with file
```
docker build -t servicetesting:0.0.1-alpine -f ./Dockerfile.alpine .
docker tag servicetesting:0.0.1-alpine sal2apao/servicetesting:0.0.1-alpine
docker push sal2apao/servicetesting:0.0.1-alpine
```
