FROM katsuhikonagashima/php-fpm-mysql:7.2-stretch

RUN apt-get install -y libpng-dev libjpeg-dev
RUN docker-php-ext-configure gd --with-png-dir=/usr/include --with-jpeg-dir=/usr/include
RUN docker-php-ext-install gd
