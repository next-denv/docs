# docs for setting up denv
This blog help you starting you journal with denv. I'll use a golang environment for example. [中文文档](./README_cn.md)

## Prerequisites
+ 1 linux server with docker [installed](https://docs.docker.com/engine/install/).

## Quick start
+ create a linux user, setup ssh info.
```shell
# create user
$ sudo adduser narro

# create user ssh fold
$ mkdir -p /root/users/narro

# ... generate your ssh private key and public key for new user narro.
```

+ run docker container using [docker-compose](https://github.com/next-denv/golang/blob/1.15.0/docker-compose.yml).
