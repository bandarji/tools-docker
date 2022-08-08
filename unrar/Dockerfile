FROM --platform=linux/arm64 ubuntu:latest
MAINTAINER Sean Jain Ellis <sellis@bandarji.com>

# RUN apk add --no-cache unrar


RUN apt update && apt install unrar
RUN mkdir /work

WORKDIR /work
