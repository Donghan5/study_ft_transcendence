FROM php:8.2-apache

RUN docker-php-ext-install pdo pdo_sqlite

COPY . /var/www/html/

RUN chown -R www-data:www-data /var/www/html
RUN chown -R 755 /var/www/html

EXPOSE 9000