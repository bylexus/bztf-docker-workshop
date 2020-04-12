FROM php:7.4-apache
RUN pecl install xdebug-2.9.2 && docker-php-ext-enable xdebug
COPY php.ini /usr/local/etc/php/php.ini
COPY apache.conf /etc/apache2/sites-available/000-default.conf
