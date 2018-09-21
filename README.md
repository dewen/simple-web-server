# Simple-Web-Server

Simple Web Server project uses Docker to quickly create environments for web development beginners.

* Simple Apache
  CMD
    ```
    docker run -p 8885:80 -v "$PWD":/var/www/html php:7.2-apache
    ````

* Apache and PHP
* Apache PHP MySQL
