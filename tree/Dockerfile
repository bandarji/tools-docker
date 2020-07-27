# tree container
# docker run --rm -v $(PWD):/treedir -it tree
#
FROM alpine:latest
MAINTAINER Sean Jain Ellis <sellis@bandarji.com>

RUN apk add --no-cache tree

RUN mkdir /treedir
WORKDIR /treedir

ENTRYPOINT ["/usr/bin/tree"]
