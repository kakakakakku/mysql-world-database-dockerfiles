# mysql-world-database-dockerfiles

[![Docker Pulls](https://img.shields.io/docker/pulls/kakakakakku/mysql-world-database.svg?style=for-the-badge)](https://hub.docker.com/r/kakakakakku/mysql-world-database/)
[![Docker Automated build](https://img.shields.io/docker/automated/kakakakakku/mysql-world-database.svg?style=for-the-badge)](https://hub.docker.com/r/kakakakakku/mysql-world-database/)

Dockerfiles for MySQL pre-loaded sample database "world database" 🐳

- [MySQL :: Other MySQL Documentation](https://dev.mysql.com/doc/index-other.html)

## Supported versions

- 5.5
- 5.6
- 5.7 (latest)
- 8.0

## Usage

```sh
$ docker pull kakakakakku/mysql-world-database
$ docker run -e MYSQL_ALLOW_EMPTY_PASSWORD=yes -d kakakakakku/mysql-world-database
$ docker exec -it $(docker container ls | grep 'kakakakakku/mysql-world-database' | awk '{print $1}') /bin/sh
```
