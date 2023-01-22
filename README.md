# Traefik in Docker Compose with no access to docker socket

A simple example of a docker-compose setup for traefik without giving traefik access to the docker socket.

The docker provider is not used at all, instead all dynamic configuration is supplied by the file provider.