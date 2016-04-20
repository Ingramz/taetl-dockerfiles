FROM docker:1.11.0

RUN apk add --update --no-cache bash

ENV COMPOSE_VERSION 1.7.0

RUN set -x \
  && curl -o /usr/local/bin/docker-compose -L "https://github.com/docker/compose/releases/download/${COMPOSE_VERSION}/docker-compose-Linux-x86_64" \
	&& chmod +x /usr/local/bin/docker-compose
