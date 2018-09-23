FROM docker.elastic.co/elasticsearch/elasticsearch:6.4.0
ADD elasticsearch.yml /usr/share/elasticsearch/config/
USER root
WORKDIR /usr/share/elasticsearch
RUN chown elasticsearch:elasticsearch config/elasticsearch.yml