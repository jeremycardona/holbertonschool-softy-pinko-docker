# Use the latest Nginx image as the base image
FROM nginx:latest

# Copy the proxy configuration file to the appropriate location in the Docker image
COPY ./proxy.conf /etc/nginx/conf.d/default.conf

EXPOSE 80