# Nginx Docker Image

This Docker image provides a minimal Nginx server based on Alpine Linux.

## Features

- Uses Alpine Linux as the base image for a lightweight container.
- Installs the latest version of Nginx.
- Includes essential prerequisites such as OpenSSL, curl, and CA certificates.
- Starts Nginx in the foreground.

## Usage

You can use this image as a base image for your NGINX server. For example, in your `Dockerfile`:

```Dockerfile
FROM nvharish/nginx-alpine:latest

# Your application-specific configurations and dependencies
