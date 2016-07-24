# Docker Ulbora Labs Nginx
- 1.0.0, latest[ (Dockerfile)](https://github.com/Ulbora/docker_ulboralabs/blob/master/Dockerfile)

This is Docker Ulbora Labs nginx on Alpine 

This image can be used for mapping multiple domains to docker containers.


# Running

```
docker run -v /data/db:/data/db -v /databackup:/databackup --name \
ulboramongo -d ulboralabs/ulboracms-mongo
```




# Connect to running instance

```
docker exec -it ulboralabs/ulboracms-nginx sh
```


