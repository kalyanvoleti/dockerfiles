FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
# This command runs whenever someone uses your image as their base OS
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]