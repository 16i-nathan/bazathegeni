# Use the official PHP image from the Docker Hub
FROM php:7.4-apache

# Install any necessary PHP extensions
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Copy your application code to the container
COPY . /var/www/html/

# Set the working directory
WORKDIR /var/www/html/

# Expose port 80
EXPOSE 80
