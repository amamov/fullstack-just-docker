# Fullstack! - Just Docker

> fullstack boilerplate based in docker environment. just docker!

- nestjs (typescript)
- nextjs (typescript)
- nginx, reverse-proxy
- docker, docker-compose, docker-swarm, docker-stack
- vscode

## Getting Start

### requirements

- installed docker, docker-compose
- settings env_files

### development mode

> `docker-compose -f dev.compose.yml up --build`

- compose logs : `docker-compose -f dev.compose.yml logs`

- compose server down : `docker-compose -f dev.compose.yml down`

- container clean up : `docker rm -f $(docker ps -aq)`

### production mode

> `docker swarm init` && `docker stack deploy -c compose.yml`
