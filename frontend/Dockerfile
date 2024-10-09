
FROM nginx:latest

COPY templates /usr/share/nginx/html
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY config.json /usr/share/nginx/html

EXPOSE 80