#Step:1 Ubuntu (base image)
FROM ubuntu:latest

#Step:2 Nginx install
RUN apt-get update
RUN apt-get install -y -q nginx

#Step:3 file copy
COPY ./index.html /usr/share/nginx/html/

EXPOSE 80

#step:4 Nginx start
CMD ["nginx", "-g", "daemon off"]
