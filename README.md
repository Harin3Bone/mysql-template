## MySQL

![Docker](https://img.shields.io/badge/Docker-2496ED?&style=flat&logo=docker&logoColor=ffffff)
![Postgres](https://img.shields.io/badge/MySQL-F7F7F7?&style=flat&logo=mysql&logoColor=336791)

## Description

Simple template of MySQL with Docker Compose

## Prerequisite

* [Docker](https://docs.docker.com/engine/install/ubuntu/)
* [Docker Compose](https://docs.docker.com/compose/install/)
* [MySQL](https://www.mysql.com/)

## Default Value

Change value in `default.env` file to define your own value

| Variable name              | Default value | Datatype |                                 Description |
|:---------------------------|:--------------|:--------:|--------------------------------------------:|
| MYSQL_VERSION              | 8.0.33        |  String  |                         MySQL image version |
| MYSQL_PORT                 | 3306          | Integer  |                                  MySQL port |
| MYSQL_ROOT_PASSWORD        | root          |  String  |                   Password for root account |
| MYSQL_DATABASE             | mydatabase    |  String  |                       Initial Database name |
| MYSQL_USER                 | myuser        |  String  |                           User account name |
| MYSQL_PASSWORD             | mypassword    |  String  |                   Password for user account |
| MYSQL_ALLOW_EMPTY_PASSWORD | `no`          |  String  |   Allow empty password <br>-`yes` <br>-`no` |

## Reference
[MySQL Docker Hub](https://hub.docker.com/_/mysql)

## Contributor

[![Github](https://img.shields.io/badge/Harin3Bone-181717?style=flat&logo=github&logoColor=ffffff)](https://github.com/Harin3Bone)
