FROM docker:1.11.0

ENV COMPOSE_VERSION 1.7.0

RUN set -x \
	&& apk add --update --no-cache bash rsync \
	&& curl -o /usr/local/bin/docker-compose -L "https://github.com/docker/compose/releases/download/${COMPOSE_VERSION}/docker-compose-Linux-x86_64" \
	&& chmod +x /usr/local/bin/docker-compose \
	&& docker-compose -v
