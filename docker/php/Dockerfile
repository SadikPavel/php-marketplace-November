FROM php:8.4-fpm-alpine

RUN docker-php-ext-install pdo pdo_mysql

COPY php.ini /usr/local/etc/php/conf.d/custom.ini

WORKDIR /var/www/html
