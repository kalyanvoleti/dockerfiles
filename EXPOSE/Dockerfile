FROM almalinux:9
RUN dnf install nginx -y
# There’s no actual functionality for EXPOSE — it’s only meant to provide information.
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]