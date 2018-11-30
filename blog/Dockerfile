FROM wordpress:latest

RUN cd /var/www/html && rm -rf *
ADD ./wordpress /var/www/html

CMD ["/usr/sbin/apache2ctl", "-DFOREGROUND"]
