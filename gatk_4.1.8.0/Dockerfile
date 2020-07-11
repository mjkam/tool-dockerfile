FROM genetica_base:1.0

RUN cd /tool && wget https://github.com/broadinstitute/gatk/releases/download/4.1.8.0/gatk-4.1.8.0.zip && \
		unzip gatk-4.1.8.0.zip && ln -s $PWD/gatk-4.1.8.0/gatk /usr/local/bin/gatk
