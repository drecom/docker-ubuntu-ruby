# docker-ubuntu-ruby
[![CircleCI](https://circleci.com/gh/drecom/docker-ubuntu-ruby/tree/master.svg?style=svg)](https://circleci.com/gh/drecom/docker-ubuntu-ruby/tree/master)

A Ubuntu ruby docker container

It's on [docker-hub](https://hub.docker.com/r/drecom/ubuntu-ruby/) and [github](https://github.com/drecom/docker-ubuntu-ruby/)

## tags and links
* `latest` [(master/Dockerfile)](https://github.com/drecom/docker-ubuntu-ruby/blob/master/Dockerfile)
* `2.3.1` [(2.3.1/Dockerfile)](https://github.com/drecom/docker-ubuntu-ruby/blob/2.3.1/Dockerfile)
* `2.3.0` [(2.3.0/Dockerfile)](https://github.com/drecom/docker-ubuntu-ruby/blob/2.3.0/Dockerfile)
* `2.2.3` [(2.2.3/Dockerfile)](https://github.com/drecom/docker-ubuntu-ruby/blob/2.2.3/Dockerfile)

## how to build

```sh
docker build --rm -t ubuntu-ruby .
```

## running

```sh
docker run -it --rm drecom/ubuntu-ruby /bin/bash
```
