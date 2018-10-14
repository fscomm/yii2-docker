FROM nginx:1.15

RUN rm /etc/nginx/conf.d/*
ADD nginx.conf /etc/nginx/nginx.conf
ADD gzip.conf /etc/nginx/conf.d/gzip.conf
