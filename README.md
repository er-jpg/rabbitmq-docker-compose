# RabbitMQ Docker Compose
A simple composer for the RabbitMQ alpine image in docker. It uses the default `guest` for username and password aling with the `5672`, `15672` default ports.

# Usage
## Requirements

 * [docker](https://www.docker.com/get-started/)
 * [docker-compose](https://docs.docker.com/compose/install/)

## Install

 * Clone and change directory into it

 ```bash
 git clone https://github.com/er-jpg/rabbitmq-docker-compose.git
 cd rabbitmq-docker-compose
 ```
 
 * Compose and run the image `docker-compose up` or detached with `docker-compose up -d`
 * Check the image status using `docker-compose ps`
 * Shutdown the image with `docker-compose down`
 * RabbitMQ UI can be acessed via `http://localhost:15672/`

---

This repo was inspired by [rycastr/postgres-docker-compose](https://github.com/rycastr/postgres-docker-compose)
