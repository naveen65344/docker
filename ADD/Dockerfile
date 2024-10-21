FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/naveen65344/docker/blob/main/RUN/Dockerfile   /usr/share/nginx/html/index.html
RUN chmod 777 /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]