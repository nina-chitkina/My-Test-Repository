FROM ubuntu:latest

RUN apt-get update


ENV TZ="Asia/Tbilisi"
ENV DEBIAN_FRONTEND="noninteractive"

RUN apt-get install -y php

EXPOSE 8080

WORKDIR /app

ADD ./index.php /app/

CMD php -S 0.0.0.0:8080
