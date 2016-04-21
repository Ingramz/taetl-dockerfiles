FROM php:fpm-alpine

RUN set -x \
	&& apk add --no-cache --update postfix \
	&& docker-php-ext-install mbstring zip pdo_mysql

CMD /etc/init.d/postfix start && php-fpm
