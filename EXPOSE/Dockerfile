FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
CMD ["nginx", "-g" "daemon off;"]

#docker inspect expose:v1 # to inspect the image
