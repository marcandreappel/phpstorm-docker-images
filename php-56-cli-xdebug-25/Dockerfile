FROM php:5.6
RUN docker-php-ext-install mysqli \
	&& pecl install xdebug-2.5.0 \
	&& docker-php-ext-enable xdebug