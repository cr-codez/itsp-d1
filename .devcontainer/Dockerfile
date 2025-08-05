FROM php:8.1-apache

# Install a few common extensions
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Enable Apache's rewrite module
RUN a2enmod rewrite

# You can add other packages and configurations here as needed
