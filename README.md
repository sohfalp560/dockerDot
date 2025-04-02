# My Dockerfiles and Container Configurations

## Overview

This repository serves as a central location for storing my Dockerfiles, `docker-compose.yml` files, and related configuration scripts used for building and running various containerized applications and services for personal projects, development environments, and specific application stacks.
- Note: I know there is some repos with various self-host files, but It is mine :)

## My base installation Method
- Note: *I'm from Iran, so I am forbidden.*


## Repository Structure
* `Commands.md`: This file contains the containers which doesn't need to start with file, so start from command. including: (Portainer-ce, )

### Folders Structures
The repository is organized by service or application. Each top-level directory typically contains:
* `docker-compose.yml` (Optional): If the service is part of a multi-container setup defined with Docker Compose.
* `Dockerfile`: The instructions to build the Docker image.
* `config/` (Optional): Directory for configuration file templates or default configs that might be copied into the image or mounted as volumes.
* `scripts/` (Optional): Helper scripts for entrypoints, health checks, or setup tasks.
* `.dockerignore`: Specifies files and directories to exclude from the build context.
* `README.md` (Optional, within the sub-directory): Specific instructions or notes for that particular service/image.