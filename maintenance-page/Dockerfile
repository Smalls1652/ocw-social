FROM docker.io/library/nginx:latest

COPY content /usr/share/nginx/html
COPY mime.types /usr/share/nginx/mime.types
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 3000
EXPOSE 4000