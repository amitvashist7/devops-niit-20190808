# Base Image.
FROM ubuntu:16.04

# Maintainer
MAINTAINER Amit <amitvashist7@gmail.com>

# Update the REPO
RUN apt-get update

# Install Apache Packages
RUN apt-get install apache2 -y 

# Copy my Web Page
COPY code.html /var/www/html/info.html

# Excute the Service 
CMD ["/usr/sbin/apache2ctl", "-D" , "FOREGROUND"]
