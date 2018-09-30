FROM docker.elastic.co/kibana/kibana:6.4.1
USER kibana
ADD kibana.yml /usr/share/kibana/config/
RUN mkdir -p /usr/share/kibana/config/certs
COPY certs /usr/share/kibana/config/certs
USER root
WORKDIR /usr/share/kibana
RUN chown kibana:kibana config/kibana.yml