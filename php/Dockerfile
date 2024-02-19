FROM php:8.1-fpm

# 安装PDO和pdo_mysql扩展
RUN docker-php-ext-install pdo pdo_mysql

# 安装Redis扩展
RUN pecl install redis && docker-php-ext-enable redis