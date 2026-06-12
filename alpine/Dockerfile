FROM docker.io/alpine:3.23
MAINTAINER Nicolae V. Cristea <cristea@enkas.tech>

RUN apk add --update \
        bash \
        htop

RUN rm -rf /var/cache/apk/* && rm -rf /tmp/*

CMD /bin/bash
