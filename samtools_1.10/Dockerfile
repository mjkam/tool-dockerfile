FROM genetica_base:1.0

RUN wget https://github.com/samtools/samtools/releases/download/1.10/samtools-1.10.tar.bz2 && tar -xf samtools-1.10.tar.bz2
RUN cd samtools-1.10 && make -j4 && make install

