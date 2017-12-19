FROM php:5.6.31-fpm
#ARG TIMEZONE = Europe/Minsk

RUN apt-get update && apt-get install -y \
    openssl \
    git \
    unzip

# Type docker-php-ext-install to see available extensions
RUN docker-php-ext-install pdo pdo_mysql