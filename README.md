# docker-php
Is a simple extended php image from [php:apache](https://github.com/docker-library/php/blob/63835823986369ab5982cc6ea1345a962fda5b4a/5.6/apache/Dockerfile)

This image has the following php extensions included:
 - iconv
 - mcrypt
 - gd
 - mysql

## Usage
### Pull from Docker Registry
```
docker pull solidnerd/php
```
or build your own by the provided Dockerfile.

### Run a container
```
docker run -d  -v $(pwd):/var/www/html solidnerd/php
```
