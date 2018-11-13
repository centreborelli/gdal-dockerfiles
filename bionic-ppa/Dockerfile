FROM ubuntu:bionic
MAINTAINER Carlo de Franchis <carlodef@gmail.com>
RUN apt-get update && apt-get install -y \
    curl \
    gdal-bin \
    git \
    libgdal-dev \
    python3 \
    python3-dev \
    vim
RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python3 get-pip.py
RUN pip install ipython
WORKDIR /root
