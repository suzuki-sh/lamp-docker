FROM php:7.4-apache

RUN apt-get update \
  && apt-get install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev libicu-dev libonig-dev\
  && docker-php-ext-install pdo_mysql mysqli gd iconv intl \
  && mv /etc/apache2/mods-available/rewrite.load /etc/apache2/mods-enabled \
  && /bin/sh -c a2enmod rewrite