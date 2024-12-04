FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://en.wikipedia.org/wiki/Main_Page /usr/share/nginx/html/index.html
CMD ["nginx" , "-g" , "daemon off;"]