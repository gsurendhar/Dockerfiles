FROM almalinux:9
RUN dnf install -y nginx
RUN rm -rf /usr/share/nginx/html/index.html
# COPY index.html /usr/share/nginx/html/index.html
COPY /qi/ /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]