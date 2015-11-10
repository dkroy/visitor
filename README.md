## Vistor

## Docker Containers
  - nginx
  - web
  - redis

# Docker Run On Server (Ubuntu)
```
$ sudo service docker start # If not already running
$ docker-compose build
$ docker-compose up -d
```

# Docker Run Locally (Mac)
```
$ docker-machine create --driver virtualbox default
$ eval "$(docker-machine env default)"
$ docker-compose build
$ docker-compose up -d
```

## Resources
  - [Docker Compose](https://docs.docker.com/compose/)
