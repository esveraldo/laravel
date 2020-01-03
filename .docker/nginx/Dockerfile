FROM nginx:1.15.9-alpine

RUN rm /etc/nginx/conf.d/default.conf
RUN usermod -u 1000 www-data

COPY ./nginx.conf /etc/nginx/conf.d
