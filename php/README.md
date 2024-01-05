# nvharish PHP-FPM Base Image

This Docker image is based on the official Alpine 3.19.0 image and includes PHP 8.3.

## Built-in PHP Modules

- Core
- ctype
- date
- filter
- hash
- iconv
- json
- libxml
- mbstring
- openssl
- pcre
- Phar
- random
- readline
- Reflection
- session
- SimpleXML
- SPL
- standard
- tokenizer
- xml
- Zend OPcache
- zlib

## Composer

This image uses Composer version 2.6.6.

## Usage

You can use this image as a base image for your PHP-FPM applications. For example, in your `Dockerfile`:

```Dockerfile
FROM nvharish/php-fpm:latest

# Your application-specific configurations and dependencies
