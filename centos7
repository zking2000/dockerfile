# Pull base image
FROM centos:latest

MAINTAINER Stephen Zhou H "stephen.h.zhou@ericsson.com"

# update source
RUN yum update

# Install curl
RUN yum install -y net-tools openssh-server initscripts
RUN service sshd start

# Expose ports.
EXPOSE 22