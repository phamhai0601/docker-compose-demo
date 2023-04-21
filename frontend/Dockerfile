FROM php:7.4-apache
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN sed -i -e 's|/var/www/html|/var/www/html/frontend/web|g' /etc/apache2/sites-available/000-default.conf

