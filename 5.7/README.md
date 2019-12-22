# docker-postgres

Example *docker-compose.yml* for **MySQL**

## Getting Started

### Prerequisites

*Docker Engine* needs to be installed on your machine ([Docker Documentation](https://docs.docker.com/)).

### Environment variables

| Variable               | Description                                                               |
| ---------------------- | ------------------------------------------------------------------------- |
| `HOST_PORT`            | Set the port of host machine                                              |
| `HOST_DB_INIT_SCRIPTS` | Set the location of initialization scripts in the host machine            |
| `MYSQL_ROOT_PASSWORD`  | Set the superuser(root)'s password                                        |
| `MYSQL_DATABASE`       | (Optional) Set the name of a database to be created on image startup      |
| `MYSQL_USER`           | (Optional) Set the username that will be granted superuser permissions for the database specified by `MYSQL_DATABASE` |
| `MYSQL_PASSWORD`       | (Optional) Set the password of the username specified by `MYSQL_USER`     |

### Get it running

```bash
docker-compose up -d
```

## References

* [MySQL official docker image](https://hub.docker.com/_/mysql)
* [Github docker-library issues](https://github.com/docker-library/mysql/issues)
