FROM php:8.0-apache as base
COPY ./src /var/www/html

RUN docker-php-ext-install mysqli
FROM ubuntu:20.04


