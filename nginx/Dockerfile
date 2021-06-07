FROM nginx:latest
WORKDIR /
COPY nginx/www /usr/share/nginx/html
COPY nginx/conf /etc/nginx/conf.d/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]