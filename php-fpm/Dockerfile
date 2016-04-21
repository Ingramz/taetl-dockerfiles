FROM php:fpm-alpine

RUN set -x \
	&& apk add --no-cache --update bash postfix \
	&& docker-php-ext-install zip pdo_mysql \
	&& ls -als /etc/init.d

CMD /etc/init.d/postfix start && php-fpm
