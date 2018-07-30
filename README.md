# docker-compose-wecenter
[wecenter](http://www.wecenter.com/) 使用docker-compose方式启动，mysql需要自己安装
## docker images
- richarvey/nginx-php-fpm:php5 用的tag不是latest是php5,因为在在最新php7.1中已经移除了mcrypt
- 具体可以查看https://github.com/docker-library/php/issues/541

## 如何启动
> -d 参数表示后台启动,如果测试不需要后台启动可以不加该参数
```shell
docker-compose up -d
```
## 开始安装
> 访问 [http://localhost/install/](http://localhost/install/)

## 管理后台
> [http://localhost/?/admin](http://localhost/?/admin)
