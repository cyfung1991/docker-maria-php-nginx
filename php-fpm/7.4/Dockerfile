FROM php:7.4-fpm
RUN apt-get update && \
    apt-get install -y zip libzip-dev libpng-dev
RUN docker-php-ext-install mysqli pdo pdo_mysql gd zip

WORKDIR /var/www/html

CMD ["php-fpm"]

EXPOSE 9000