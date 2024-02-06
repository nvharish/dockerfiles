# Dockerfiles for Programming Languages and Web Servers

This repository contains Dockerfiles for building Docker images with various programming languages and web servers.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
  - [Building Docker Images](#building-docker-images)
  - [Running Docker Containers](#running-docker-containers)
- [Available Dockerfiles](#available-dockerfiles)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Dockerfiles repository! Here, you'll find Dockerfiles for different programming languages and web servers, allowing you to easily containerize applications and services.

## Usage

### Building Docker Images

To build a Docker image, navigate to the directory of the desired language or web server and use the following command:

```bash
docker build -t <image-name> .
```

Replace <image-name> with a meaningful name for your Docker image.

## Running Docker Containers
After building the Docker image, you can run a container using the following command:

```bash
docker run -d -p <host-port>:<container-port> <image-name>
```

Replace <host-port> and <container-port> with the desired port mappings, and <image-name> with the name of the Docker image you built.

## Available Dockerfiles
- Node.js: Dockerfile for Node.js with npm.
- PHP: Dockerfile for PHP-FPM with composer.
- Nginx: Dockerfile for the Nginx web server.
- MySQL: Dockerfile for the MySQL database.

Feel free to explore each subdirectory for detailed instructions on building and running Docker images for specific programming languages and web servers.

## Contributing
If you have additional Dockerfiles or improvements to existing ones, feel free to contribute by submitting a pull request.

## License
This repository and its contents are licensed under the MIT License.
