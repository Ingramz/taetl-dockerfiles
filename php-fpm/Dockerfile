FROM php:fpm

RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y zlib1g-dev postfix
RUN docker-php-ext-install mbstring zip pdo_mysql

CMD service postfix start && php-fpm
