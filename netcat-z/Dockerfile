# Vintage netcat container
# docker run nc-z host port
#
FROM centos:centos6
MAINTAINER Sean Jain Ellis <sellis@bandarji.com>

RUN yum install -y nc
ENTRYPOINT ["/usr/bin/nc", "-z"]
