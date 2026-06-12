FROM docker.io/registry:3

## Config file
# https://distribution.github.io/distribution/about/configuration/

ENV REGISTRY_HTTP_TLS_LETSENCRYPT_HOSTS_0=registry.enkas.eu
ENV OTEL_TRACES_EXPORTER=none

ADD config.yml /etc/distribution/
ADD ui/certs /certs
ADD Makefile /

EXPOSE 5000
