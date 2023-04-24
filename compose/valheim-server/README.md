# Valheim-Server

Special thanks to [lloesche](https://github.com/lloesche) for making the container.

## Links
lloesche/valheim-server: [Docker Image](https://hub.docker.com/r/lloesche/valheim-server), [Github Source](https://github.com/lloesche/valheim-server-docker)

## Requirements

- Docker with Compose
- 

## Instructions

1. Copy `docker-compose.yml` and `valheim.env` to the file you want to store game data in.
```
curl -OL https://github.com/mosesprime/docker-config/compose/valheim-server/
```
2. Edit configurations to your liking. [see here for additional options](https://github.com/lloesche/valheim-server-docker#environment-variables)
3. Run it. Optional `-d`
```
docker compose up -d
```