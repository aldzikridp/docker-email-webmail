FROM php:8.2-apache
RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN cp /etc/apache2/mods-available/ssl.conf /etc/apache2/mods-enabled/ssl.conf
RUN cp /etc/apache2/mods-available/ssl.load /etc/apache2/mods-enabled/ssl.load
RUN cp /etc/apache2/mods-available/socache_shmcb.load /etc/apache2/mods-enabled/socache_shmcb.load
