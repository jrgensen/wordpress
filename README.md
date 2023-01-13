# WordPress development in Docker

Setup for local WordPress development.

The `docker-compose.yml` in this repository will bring up a fresh WordPress installation, a MySQL compatible MariaDB database and a phpMyAdmin interface.

## Requirements

- Docker

To install docker and docker-compose, follow the instructions at https://docs.docker.com/engine/installation to install into the difference OS

## How To

Open terminal, change directory to the project folder and run command

```console
$ docker-compose up -d
```

Now you have access to

- WordPress website [localhost:8080](http://localhost:8080/)
- phpMyAdmin for easy DB access [localhost:8081](http://localhost:8081)

## Directory

WordPress installation in `wordpress` folder in project root.

