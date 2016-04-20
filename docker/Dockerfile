FROM docker:1.11.0

ENV COMPOSE_VERSION 1.7.0

RUN set -x \
	&& apk add --update --no-cache bash rsync py-pip \
	&& pip install docker-compose
	&& docker-compose -v
