DockerFile for invoice ninja (https://www.invoiceninja.com/)

This image is based on `php:7` official version.

The easiest way to try this image is via docker compose :

## Prerequisites
place your cert files in: 

`/usr/share/nginx/html/codelabs/src/cert/*`

set Environment variable for MYSQL_ROOT_PASSWORD in your shell.

`export MYSQL_ROOT_PASSWORD=mysecretpassword`


```
docker-compose up -d
```
