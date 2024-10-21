FROM almalinux
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD  https://github.com/naveen65344/docker/tree/main/COPY    /usr/share/nginx/html/index.html

RUN 777  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
