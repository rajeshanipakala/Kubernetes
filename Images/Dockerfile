FROM ubuntu:16.04
MAINTAINER Rajesh
ENV START_FOLDER /var/www
RUN apt-get update && apt-get install apache2 -y
EXPOSE 81
WORKDIR /var/www
ENTRYPOINT [ "echo" ]
CMD [${START_FOLDER}]