# Traefik configuration with Docker Compose

## Prerequisites

### `.env` file

Create an `.env` file based on `template.env` and add your hostname.

### `acme.json` file

Create an empty file called `acme.json` with permissions 600.

## Run traefik

```shell
docker-compose up -d
```

This will start the traefik service and publish a dashboard to `https://traefik.<your hostname>`.
