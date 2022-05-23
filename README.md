# elartic-services

I'll be hosting multiple services using docker and docker compose, here is my configuration.  
Most of the code I have here comes from the documentation link to Nextcloud, Nginx and nginx-proxy.

## What I plan to do

For now I must have a Nextcloud to sync all my important files between my devices. In the future I'd like to host a Gitlab too.

## Containers that I use

* [mariadb](https://hub.docker.com/_/mariadb)
* [redis](https://hub.docker.com/_/redis)
* [nextcloud:fpm-alpine](https://hub.docker.com/_/nextcloud)
* [nginx:alpine](https://hub.docker.com/_/nginx)
* [ngninx-proxy:alpine](https://github.com/nginx-proxy/nginx-proxy)
* [acme-companion](https://github.com/nginx-proxy/acme-companion)

## `db.env` file

```
MYSQL_ROOT_PASSWORD=
MYSQL_PASSWORD=
MYSQL_DATABASE=
MYSQL_USER=
```
