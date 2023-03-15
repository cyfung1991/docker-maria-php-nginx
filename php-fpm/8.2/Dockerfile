FROM php:8-fpm
RUN apt-get update && \
    apt-get install -y zip libzip-dev libpng-dev
RUN docker-php-ext-install mysqli pdo pdo_mysql gd zip

WORKDIR /var/www

CMD ["php-fpm"]

EXPOSE 9000