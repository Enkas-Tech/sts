FROM docker.io/quiq/docker-registry-ui:latest

ENV REGISTRY_HOSTNAME=192.168.50.10:5000
ENV REGISTRY_INSECURE=true

ADD config.yml /opt/
ADD certs /

EXPOSE 8000
