# syntax=docker/dockerfile:1 
FROM nginx:1.29.4-alpine3.23 as deploy
WORKDIR /app
EXPOSE 80
COPY ./app/build/devbox/docs ./static/devbox/docs/
COPY ./nginx.conf /etc/nginx/nginx.conf
