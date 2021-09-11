FROM php:7.4-fpm

# Install required PHP extensions
RUN apt-get -y update \
&& apt-get install -y libicu-dev libzip-dev \
&& docker-php-ext-install zip pdo_mysql mysqli \
&& docker-php-ext-configure intl \
&& docker-php-ext-install intl \