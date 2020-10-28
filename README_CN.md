# docker-redis-cluster

[中文文档](./README_CN.md)

[![Docker Stars](https://img.shields.io/docker/stars/grokzen/redis-cluster.svg)](https://hub.docker.com/r/grokzen/redis-cluster/)
[![Docker Pulls](https://img.shields.io/docker/pulls/grokzen/redis-cluster.svg)](https://hub.docker.com/r/grokzen/redis-cluster/)
[![Build Status](https://travis-ci.org/Grokzen/docker-redis-cluster.svg?branch=master)](https://travis-ci.org/Grokzen/docker-redis-cluster)

Docker image with redis built and installed from source and a cluster is built.

所有版本 https://github.com/antirez/redis/releases

### 注意事项

获取服务器节点如果不是`host`模式获取的是容器内部的IP


### 使用

1. 构建镜像  `make build`
2. 启动服务 `make up`