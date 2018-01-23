# rachel-resources
Rachel resources (Dockerfile, docker-compose, configs...)

# Links

* Yair: https://github.com/yfoelling/yair
* ClairDB: https://hub.docker.com/r/arminc/clair-db/

# Setup
`docker-compose up`

# Run yair (analyze images and return JSON)
```
docker run -v `pwd`/config/:/opt/yair/config/:ro  yfoelling/yair nginx
```
