FROM almalinux:9
RUN dnf install nginx -y
# there is no functionality for EXPOSE it is just for information only
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]