FROM php:7.4-fpm-alpine

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN mkdir /info
WORKDIR /info
run echo "<?php phpinfo();" > index.php

WORKDIR /src
