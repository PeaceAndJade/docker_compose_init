FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.2

# RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.5.2/elasticsearch-analysis-ik-6.5.2.zip

RUN mkdir /usr/share/elasticsearch/plugins/analysis-ik
RUN cd /usr/share/elasticsearch/plugins/analysis-ik && \
    wget https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.5.2/elasticsearch-analysis-ik-6.5.2.zip && \
    unzip elasticsearch-analysis-ik-6.5.2.zip
