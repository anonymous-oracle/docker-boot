FROM ubuntu

LABEL MAINTAINER="anonymous-oracle"

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get -y install nginx
ADD nginx-basics /


ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off"]
EXPOSE 80
