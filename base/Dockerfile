FROM ubuntu

RUN apt-get update && export DEBIAN_FRONTEND="noninteractive" && apt-get install -y tzdata
RUN apt-get install -y \
    wget bzip2 make gcc zlib1g-dev git libncurses-dev libbz2-dev lzma liblzma-dev libcurl4-openssl-dev \
    r-base python-is-python3 unzip curl openjdk-11-jdk

RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip && ./aws/install

RUN mkdir /genetica && mkdir /tool
WORKDIR /genetica
