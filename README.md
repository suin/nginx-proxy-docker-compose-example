# nginx-proxy and Docker Compose Example

This is an example to show how to use nginx-proxy in docker-compose.

## How to demo it

Create network

```
docker network create --driver bridge shared
```

Run shared services

```
cd shared
docker-compose up -d
```

Run application services

```
cd app1
docker-compose up -d
```