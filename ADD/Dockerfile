FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/kalyanvoleti/dockerfiles/bf9bbfa54dfb982d2a58b6e7dcddc8ba50a8e1db/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD demo-text-files.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]