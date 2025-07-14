FROM almalinux:9
RUN dnf install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/gsurendhar/Shell-Script-Practice/refs/heads/master/README.md /usr/share/nginx/html/index.html
RUN chmod +r http://3.86.251.67:8080/
CMD ["nginx", "-g", "daemon off;"]