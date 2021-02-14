FROM php:7.4-fpm
EXPOSE 9000
EXPOSE 9003
WORKDIR /app
COPY . /app
RUN pecl install xdebug-3.0.2 \
    && docker-php-ext-enable xdebug