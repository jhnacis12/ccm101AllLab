# Docker Compose Guide

## What is Docker Compose?

Docker Compose is a tool used to define and run multiple Docker containers using a configuration file. In this mission, Docker Compose was used to deploy Nextcloud and MariaDB together.

## The services: Block

The `services:` block defines the containers that will be created and managed by Docker Compose.

In this project, there are two services:

- `database`
- `app`

The `database` service uses the MariaDB 10.6 image, while the `app` service uses the Nextcloud image.

## Database Service

The database service uses:

```yaml
image: mariadb:10.6
