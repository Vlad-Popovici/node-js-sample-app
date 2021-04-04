FROM Node:15.13.0-alpine3.10 as builder

COPY . /cart-app

WORKDIR /cart-app

RUN node cart-app.js

EXPOSE 80
