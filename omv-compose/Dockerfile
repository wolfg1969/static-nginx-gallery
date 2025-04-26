FROM openresty/openresty:alpine-fat

RUN sed -i 's#https\?://dl-cdn.alpinelinux.org/alpine#https://mirrors.tuna.tsinghua.edu.cn/alpine#g' /etc/apk/repositories
RUN apk add --update --no-cache make g++ python3 py3-pip
RUN apk add --update --no-cache nodejs npm
RUN apk add --update --no-cache ffmpeg
