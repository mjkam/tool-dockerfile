FROM genetica_base:1.0

RUN wget https://github.com/lh3/bwa/releases/download/v0.7.17/bwa-0.7.17.tar.bz2
RUN tar -xf bwa-0.7.17.tar.bz2
RUN cd bwa-0.7.17 && make -j4 && mv bwa /usr/local/bin
RUN git clone https://github.com/lh3/bwa-docker.git
