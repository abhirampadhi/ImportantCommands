# Docker Command List

This document provides a complete list of common Docker commands.

## Table of Contents

- [Basic Commands](#basic-commands)
- [Container Commands](#container-commands)
- [Image Commands](#image-commands)
- [Volume Commands](#volume-commands)
- [Network Commands](#network-commands)
- [Docker Compose Commands](#docker-compose-commands)

## Basic Commands

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `docker --version`                   | Show the Docker version.                             |
| `docker info`                        | Display system-wide information about Docker.       |
| `docker help`                        | Get help for Docker commands.                        |

## Container Commands

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `docker run <image>`                 | Run a container from a specified image.             |
| `docker ps`                           | List running containers.                             |
| `docker ps -a`                        | List all containers (running and stopped).          |
| `docker stop <container_id>`         | Stop a running container.                            |
| `docker start <container_id>`        | Start a stopped container.                           |
| `docker restart <container_id>`      | Restart a container.                                |
| `docker rm <container_id>`           | Remove a stopped container.                          |
| `docker logs <container_id>`         | View logs for a container.                           |
| `docker exec -it <container_id> <cmd>` | Execute a command inside a running container.    |

## Image Commands

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `docker images`                       | List all images on the local machine.              |
| `docker pull <image>`                | Download an image from Docker Hub.                  |
| `docker rmi <image_id>`              | Remove a specified image.                            |
| `docker build -t <image_name> .`    | Build an image from a Dockerfile in the current directory. |
| `docker tag <image> <new_image>`     | Tag an image with a new name.                       |

## Volume Commands

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `docker volume ls`                   | List all Docker volumes.                             |
| `docker volume create <volume_name>` | Create a new Docker volume.                          |
| `docker volume rm <volume_name>`     | Remove a specified Docker volume.                   |
| `docker volume inspect <volume_name>` | Show detailed information about a volume.           |

## Network Commands

| Command                               | Description                                          |
|---------------------------------------|------------------------------------------------------|
| `docker network ls`                  | List all Docker networks.                            |
| `docker network create <network_name>` | Create a new Docker network.                       |
| `docker network rm <network_name>`   | Remove a specified Docker network.                  |
| `docker network inspect <network_name>` | Show detailed information about a network.        |

## Docker Compose Commands

| Command                                   | Description                                          |
|-------------------------------------------|------------------------------------------------------|
| `docker-compose up`                       | Start services defined in a `docker-compose.yml` file. |
| `docker-compose down`                     | Stop and remove services defined in a `docker-compose.yml`. |
| `docker-compose build`                   | Build or rebuild services defined in a `docker-compose.yml`. |
| `docker-compose logs`                    | View output from containers defined in a `docker-compose.yml`. |
| `docker-compose ps`                      | List containers managed by `docker-compose`.       |

---
