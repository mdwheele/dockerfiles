FROM ubuntu:xenial
MAINTAINER Dustin Wheeler "mdwheele@ncsu.edu"
USER root

# Update and set locale
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update
ENV LANG en_US.UTF-8

# Install Xmind
RUN apt-get -y install rsync unzip curl
RUN curl -L https://www.xmind.net/xmind/downloads/xmind-8-beta-linux_amd64.deb --output xmind-8-beta-linux_amd64.deb
RUN apt -y install ./xmind-8-beta-linux_amd64.deb

CMD ["/usr/bin/XMind"]