# docker-compose-wecenter
wecenter docker compose
## docker images
- richarvey/nginx-php-fpm:php5 用户的php5,因为在php7.1中已经移除了mcrypt
- 具体可以查看https://github.com/docker-library/php/issues/541

## 如何启动
```shell
docker-compose up -d
```
## 开始暗装
> http://localhost/install/
