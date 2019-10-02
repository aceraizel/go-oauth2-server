# OAUTH2 Server - Golang

## Setup
Use [docker-compose](https://docs.docker.com/compose/) to start the app, postgres, etcd in separate linked containers via network:

```sh
docker-compose up -d
```

Check api works:

```sh
http://localhost:8080/v1/health
```
