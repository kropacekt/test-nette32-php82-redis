FROM php:8.3-apache

RUN \
  apt-get update && \
  pecl install redis && \
  docker-php-ext-enable redis