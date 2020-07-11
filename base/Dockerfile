FROM ubuntu

RUN apt-get update && apt-get install -y \
    wget bzip2 make gcc zlib1g-dev git libncurses-dev libbz2-dev lzma liblzma-dev libcurl4-openssl-dev

RUN DEBIAN_FRONTEND="noninteractive" apt-get install -y openjdk-8-jdk

RUN mkdir /genetica && mkdir /tool
WORKDIR /genetica
