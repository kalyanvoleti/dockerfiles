FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
#this executes when any user uses your image as their base os
CMD ["nginx", "-g", "daemon off;"]