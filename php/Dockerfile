FROM php:7.4-fpm

RUN apt-get update && apt-get install -y libpq-dev libzip-dev libpng-dev libgd-dev libicu-dev libxml2-dev
RUN docker-php-ext-install soap xmlrpc intl gd mysqli pdo_mysql pdo_pgsql zip

COPY php.ini /usr/local/etc/php/conf.d/custom-php.ini
