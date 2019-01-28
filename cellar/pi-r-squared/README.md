# pi-r-squared

This is a local docker-engine host on a raspberry-pi 3 in the "SWX Data" data science network.

## environment

Before running `docker-compose` in this directory, please be sure to source the dm:

    [sofwerx::] icbmbp:pi-r-squared ianblenke$ swx dm env pi-r-squared
    [sofwerx:pi-r-squared:pi-r-squared] icbmbp:pi-r-squared ianblenke$

Due to `DOCKER_COMPOSE=pi-r-squared.yml` in the pi-r-squared environment, the `pi-r-squared.yml` here is the `docker-compose.yml` that is used when a `docker-compose` is run.

This docker-compose will spin up a traefik SSL reverse proxy that will allocate an SSL cert automatically from Let's Encrypt using ACME.

