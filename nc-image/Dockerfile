FROM nextcloud:18.0.3-apache

COPY nc-apache.conf /etc/apache2/sites-available/

RUN a2dissite 000-default
RUN a2ensite nc-apache
RUN a2enmod ssl

