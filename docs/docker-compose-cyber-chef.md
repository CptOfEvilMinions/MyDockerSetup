# Cyber Chef

This docker-compose is demonstrating how to connect a seperate docker-compose stack to the Traefik reverse proxy. Even if you run Traefik using `v3` you can still connect `v2.2` docker stacks.

## Docker-compose v2
1. `docker-compose -f docker-compose-cyber-chef.yml up`

## Docker-compose v3
1. `docker-compose -f docker-compose-cyber-chef-v3.yml up`