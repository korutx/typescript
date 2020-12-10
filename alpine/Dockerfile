FROM node:lts-alpine

RUN apk add --no-cache --virtual .persistent-deps \
    openssl \
    make \
    gcc \
    g++ \
    python \
    py-pip \
    && npm install -g npm \
    && npm install --silent --save-dev -g  typescript