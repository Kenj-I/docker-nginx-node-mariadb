# docker-nginx-node-mariadb

## usage

### vue

すでにプロジェクト等ある場合は
```shell
$ docker-compose build
$ docker-compose up -d
```
ない場合

```shell
$ docker-compose build
$ docker-compose run --rm -v ./project:/usr/src/app -w /usr/src/app app vue init webpack .
```
