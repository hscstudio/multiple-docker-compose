# Multiple Docker Compose

## CREATE NETWORK GATEWAY
docker network create cais-nginx-network

## RUN APP1

```
cd app1
docker compose up -d
```

## RUN APP2

```
cd app2
docker compose up -d
```

## RUN NGINX

```
cd ..
docker compose up -d
```

## ACCESS APP 1
http://localhost/app1

## ACCESS APP 2
http://localhost/app2

