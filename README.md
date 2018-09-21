# Simple-Web-Server

Simple Web Server project uses Docker to quickly create environments for web development beginners.
## Prerequisite 
You need to install Docker on your computer first:
* Mac
  https://docs.docker.com/docker-for-mac/install/
* Windows
  https://docs.docker.com/docker-for-windows/install/

## Simple Apache
Steps to start with your project
1. Open a terminal/console on your computer.
2. Go to your working directory. i.e. 
```
cd /Users/dewen/sandbox/project_1/
```
3. Work on your web HTML files under the folder, i.e. index.html
```
echo '<h1>Project One</h1>' > index.html
```
4. Start your web server instance from current directory.
```
docker run -p 8885:80 -v "$PWD":/var/www/html php:7.2-apache
````
5. Check your web site on a browser. i.e.
```
open http://localhost:8885/index.html
```
*`open` command may not be available in your case, if so, just copy paste the url in your browser.*

6. To stop the instance, press ctrl + 'c' to exit the process.

## Apache and PHP
## Apache PHP MySQL
