FROM php:7.4-apache
COPY . /var/www/html/
RUN echo "ServerName localhost" >> /etc/apache2/apache2.conf
RUN service apache2 restart
EXPOSE 80
