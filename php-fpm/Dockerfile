FROM php:fpm

RUN apt-get update
RUN apt-get install -y zlib1g-dev ssmtp
RUN docker-php-ext-install mbstring zip pdo_mysql
