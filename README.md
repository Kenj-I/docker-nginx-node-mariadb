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
$ docker-compose run app npm install -g vue-cli && vue init webpack ./
```
