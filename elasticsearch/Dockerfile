FROM docker.elastic.co/elasticsearch/elasticsearch:6.4.1
USER elasticsearch
ADD elasticsearch.yml /usr/share/elasticsearch/config/
RUN mkdir -p /usr/share/elasticsearch/config/certs
COPY certs /usr/share/elasticsearch/config/certs
USER root
WORKDIR /usr/share/elasticsearch
RUN chown elasticsearch:elasticsearch config/elasticsearch.yml