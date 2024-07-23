# syntax=docker/dockerfile:1 
FROM nginx:1.26.1-alpine3.19 as deploy
WORKDIR /app
EXPOSE 80
COPY ./app/build/devbox/docs ./static/devbox/docs/
COPY ./nginx.conf /etc/nginx/nginx.conf
