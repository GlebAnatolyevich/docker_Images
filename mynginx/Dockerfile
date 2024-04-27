# Version: 0.0.1
FROM ubuntu:22.04:12-alpine AS build
MAINTAINER Yuri Trukhin <trukhinyuri@infoboxcloud.com>
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Hi, I am in your container' \
        >/usr/share/nginx/html/index.html
EXPOSE 80