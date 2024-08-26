# Using Nginx image as the base image
FROM nginx:latest

# Coping the front-end files to web server directory
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy Nginx config files
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf