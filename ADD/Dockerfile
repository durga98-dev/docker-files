FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/durga98-dev/docker-files/blob/618cc067e847f320ddcca0d7fbf9b1e47b6812b7/COPY/index.html /usr/share/nginx/html/index.html
RUN chmod -x /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]