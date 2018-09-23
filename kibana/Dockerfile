FROM docker.elastic.co/kibana/kibana:6.4.1
ADD kibana.yml /usr/share/kibana/config/
USER root
WORKDIR /usr/share/kibana
RUN chown kibana:kibana config/kibana.yml