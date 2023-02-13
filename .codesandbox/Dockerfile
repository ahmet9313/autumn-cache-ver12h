FROM php:5.6-apache

RUN apt-get update && apt-get install -y nodejs npm
#WORKDIR is /var/www/html
COPY . /var/www/html/
RUN npm install
