# fping container
# docker run fping -ale {this,that}-host.example.com
#
FROM alpine:latest
MAINTAINER Sean Jain Ellis <sellis@bandarji.com>

RUN apk add --no-cache fping
ENTRYPOINT ["/usr/sbin/fping"]

