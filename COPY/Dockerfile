FROM almalinux:9
RUN dnf install nginx -y
COPY index.html /usr/share/html/index.html
CMD ["nginx", "-g", "daemon off;"]