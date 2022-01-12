# Lavamusic on docker compose
This library aims to simplify setting up a new music bot using docker compose and [lavamusic](https://github.com/brblacky/lavamusic).

## Prerequisites
- [Docker](https://www.docker.com/get-started)
- [discord bot token](https://discord.com/developers/applications)

## Configuration
- Put your discord bot token in [.env](.env) TOKEN
- Replace the passwords
  - mongo password in [docker-compose.yml](docker-compose.yml) and [.env](.env) MONGO_URI
  - lavalink password in [application.yml](application.yml) password and [.env](.env) NODE_PASSWORD
- See https://github.com/brblacky/lavamusic#-main for the other configuration options

## Run the application
```shell
docker compose up
```

