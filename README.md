DockerFile for invoice ninja (https://www.invoiceninja.com/)

This image is based on `php:7` official version.

The easiest way to try this image is via docker compose :

## Prerequisites
place your cert files in: 

`/usr/share/html/time/cert/*`

set Environment variable for MYSQL_ROOT_PASSWORD inside a file called .env

`
$ cat .env
MYSQL_ROOT_PASSWORD=mysecretpassword
MYSQL_DATABASE=mydatabasename
`


```
docker-compose up -d
```
