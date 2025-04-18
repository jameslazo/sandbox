FROM ubuntu:20.04

RUN apt-get update && apt-get install curl -y

ARG go_ver=go1.24.0

RUN curl -OL https://golang.org/dl/${go_ver}.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf ${go_ver}.linux-amd64.tar.gz && \
    rm ${go_ver}.linux-amd64.tar.gz
ENV PATH="/usr/local/go/bin:$PATH"

# Install Python and pip packages
RUN apt-get install -y \
    python3 python3-pip && \
    pip3 install --no-cache-dir requests numpy
