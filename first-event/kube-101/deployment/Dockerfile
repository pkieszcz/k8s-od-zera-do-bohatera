FROM ubuntu
MAINTAINER Piotr Kieszczynski (piotr.kieszczynski@nordcloud.com)
RUN apt-get update
RUN apt-get install -y nginx
COPY html /var/www/html
ENTRYPOINT ["/usr/sbin/nginx","-g","daemon off;"]
EXPOSE 80
