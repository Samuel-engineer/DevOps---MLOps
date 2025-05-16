# Use nginx base image
FROM httpd:2.4-alpine

# Copy your index.html into the container's nginx html directory
COPY ./index.html /usr/local/apache2/htdocs/
COPY ./config/httpd.conf /usr/local/apache2/conf/httpd.conf
