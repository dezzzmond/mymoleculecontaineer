FROM ubuntu:18.04
ENV LANG C.UTF-8

RUN apt-get update

RUN apt-get install \
    sudo \
    python3 \
    python3-pip \
    python3-venv \
    python3-dev \
    python3-setuptools \
    python3-lib2to3 \
    python3-distutils \
    -y \
    && apt-get clean \
    && rm -rf /var/cache/apt/
