FROM ubuntu:26.04

RUN apt-get update -y \
    && apt-get install -y curl

RUN cd /tmp/ && \
    curl -OL https://github.com/gohugoio/hugo/releases/download/v0.56.1/hugo_extended_0.56.1_Linux-64bit.tar.gz && \
    tar -xf hugo_extended_0.56.1_Linux-64bit.tar.gz hugo && \
    mv hugo /usr/bin/hugo && \
    rm -rf hugo_extended_0.56.1_Linux-64bit.tar.gz
