FROM almalinux:9
RUN dnf install -y nginx
COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]