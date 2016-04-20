FROM docker:1.11.0

RUN set -x \
	&& apk add --update --no-cache bash rsync py-pip \
	&& pip install docker-compose \
	&& docker-compose -v
