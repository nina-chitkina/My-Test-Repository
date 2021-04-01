FROM ubuntu:latest

RUN apt-get update # buildkit

RUN apt-get install -y wget unzip # buildkit

ENV DEBIAN_FRONTEND=noninteractive

WORKDIR /tmp

RUN wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip && unzip ngrok-stable-linux-amd64.zip && rm ngrok-stable-linux-amd64.zip && mv ngrok /bin/ # buildkit

WORKDIR /app

# CMD ["ngrok", "http", "8080"]

