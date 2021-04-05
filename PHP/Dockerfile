FROM ubuntu:latest

RUN apt-get update


ENV TZ="Asia/Tbilisi"
ENV DEBIAN_FRONTEND="noninteractive"

RUN apt-get install -y php



WORKDIR /app

ADD ./index.php /app/

EXPOSE 8080