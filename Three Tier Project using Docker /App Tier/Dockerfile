FROM php:8.1-fpm

# Install the mysqli extension
RUN docker-php-ext-install mysqli

# Set the working directory
WORKDIR /var/www/html

# Copy application files
COPY . /var/www/html

