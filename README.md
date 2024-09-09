# Bedrock setup for WordPress using Docker

This repository contains a **Bedrock WordPress** project running inside **Docker** containers. It leverages **Docker Compose** to manage the environment and provides an easy-to-set-up development environment for WordPress with Bedrock.

## Requirements

Before starting, make sure you have the following installed on your machine:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/)

## Configuration
- [Git Clone] https://github.com/roots/bedrock.git
- Build PHP Docker Image
- Update the docker-compose.yml

## Project Structure

```plaintext
.
├── docker-compose.yml      # Docker Compose configuration
├── Dockerfile              # Docker Image
├── .env                    # Environment variables for Docker and WordPress
├── web                     # Web directory (contains WordPress files)
│   ├── app                 # Custom WordPress themes and plugins
│   ├── wp                  # WordPress core files
│   ├── index.php           # Entry point for WordPress
├── config                  # Bedrock configuration files
└── logs                    # Log files for Nginx and PHP
