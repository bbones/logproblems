FROM nginx:latest
WORKDIR /
COPY nginxrp/conf /etc/nginx/conf.d/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]