# nvharish PHP-FPM Base Image

This Docker image is based on the official Alpine latest image and includes latest version of PHP & PHP-FPM with composer.

## Built-in PHP Modules

- Core
- date
- filter
- hash
- json
- libxml
- pcre
- random
- readline
- Reflection
- SPL
- standard
- zlib

## Composer

This image uses Composer version 2.6.6.

## Usage

You can use this image as a base image for your PHP-FPM applications. For example, in your `Dockerfile`:

```Dockerfile
FROM nvharish/php-fpm-alpine:latest

# Your application-specific configurations and dependencies
