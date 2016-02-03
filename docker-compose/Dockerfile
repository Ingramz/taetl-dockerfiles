FROM docker:latest

RUN apk add --update --no-cache bash

ENV COMPOSE_VERSION 1.5.2

RUN curl -o /usr/local/bin/docker-compose -L \
		"https://github.com/docker/compose/releases/download/${COMPOSE_VERSION}/docker-compose-Linux-x86_64" \
	&& chmod +x /usr/local/bin/docker-compose

RUN ln -sf bash /bin/sh
