# Simple-Web-Server

Simple Web Server project uses Docker to quickly create environments for web development beginners.

## Simple Apache
Steps to start with your project
1. Open a terminal/console on your computer.
2. Go to your working directory. i.e. 
```
cd /Users/dewen/sandbox/project_1/
```
3. Work on your web HTML files under the folder, i.e. index.html
4. Start your web server instance from current directory.
```
docker run -p 8885:80 -v "$PWD":/var/www/html php:7.2-apache
````
5. Check your web site on a browser.
```
http://localhost:8885/index.html
```

* Apache and PHP
* Apache PHP MySQL
