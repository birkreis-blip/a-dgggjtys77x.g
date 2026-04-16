FROM php:8.2-apache

# Copy all files into the web server directory
COPY . /var/www/html/

# Fix permissions (optional but safer)
RUN chown -R www-data:www-data /var/www/html
