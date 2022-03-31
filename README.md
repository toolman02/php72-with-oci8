# php72-with-oci8

Based on php:7.2-apache image

Apache/2.4.38, Php 7.2.30, Oracle Instantclient 19.3.0.0.0

Example usage:

docker run -d --name=php72 -v /home/user/source:/var/www/html -p 8080:80 toolman02/php72-with-oci8

Assuming you have index.html or index.php in /home/user/source, open your browser to http://localhost:8080
