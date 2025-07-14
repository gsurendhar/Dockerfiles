FROM almalinux:9
RUN dnf install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/gsurendhar/Shell-Script-Practice/refs/heads/master/README.md /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]