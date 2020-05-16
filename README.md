# MyDockerSetup

## Blog post
* [My Homelab Docker setup](https://holdmybeersecurity.com/2020/05/15/my-homelab-docker-setup/)

## Docker images are pinned in `.env`
```
CONFLUENT_VERSION=5.5.0
LOGSTASH_VERSION=7.6.2
ROOT_LOGLEVEL=ERROR
NGINX_VERSION=1.18.0-alpine
MYSQL_VERSION=5.7
KOLIDE_FLEET_VERSION=2.5.0
```

## Generate OpenSSL certs
1. `openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -keyout conf/ssl/docker.key -out conf/ssl/docker.crt`
1. `openssl dhparam -out conf/nginx/ssl/dhparam.pem 2048`

## Docker-compose v2 stack commands
1. `docker-compose -f <docker-compose file> build`
1. `docker-compose -f <docker-compose file> up`

## Docker-compose v3 stack commands
1. `docker stack deploy -c <docker-compose file> <stack name>`
1. `docker stack rm <stack name>`

## Referenecs
* [docker stack rm](https://docs.docker.com/engine/reference/commandline/stack_rm/)
* []()
* []()
* []()