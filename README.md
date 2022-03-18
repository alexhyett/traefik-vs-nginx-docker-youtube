# traefik-vs-nginx-docker-youtube

Examples showing how to use Traefik and Nginx for Reverse Proxy.

This repository is to complement my YouTube video on this topic, [Traefik vs nginx: Docker Reverse Proxy](https://www.youtube.com/channel/UCm6lURZOeBVCZ5hJpqlUB-g)

## nginx

```
docker-compose -f docker-compose.nginx.yml up
```

## nginx proxy

```
docker-compose -f docker-compose.nginx-proxy.yml up
```

## traefik

```
docker-compose -f docker-compose.traefik.yml up
```

## traefik with docker network

```
docker-compose -f docker-compose.traefik-network.yml up &
docker-compose -f docker-compose.services.yml up
```