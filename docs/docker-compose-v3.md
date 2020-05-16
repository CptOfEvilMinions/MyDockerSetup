# Docker compose v3

THis example shows how to use secrets, configs, networks, and Docker stack

## Add config
1. cat `conf/nginx/nginx.conf | docker config nginx-main-conf -`

## Add secret
1. cat `conf/nginx/ss/nginx.cert | docker secret -`
1. cat `conf/nginx/ss/nginx.pub | docker secret -`

## Spin up stack



## References
