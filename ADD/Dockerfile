FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/kalyanvoleti/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD mydata.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
