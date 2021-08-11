# docker build -t raw-php .
# docker run -p 8080:80 --name raw-php-one -v="$(pwd)"/:/var/www/html raw-php

FROM php:7.3.3-apache
RUN docker-php-ext-install mysqli
EXPOSE 80
