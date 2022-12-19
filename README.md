# Event website

- Install apache2/nginx on ubuntu 20.04 lts server.
- Install php 7.2 with all plugins including mysql plugin.
- Install mysql 5.7 set root password,enter as a root create a database for your php website,create a user and grant privileges to user of that database.
- Install git and pull the code from the git repository and move or copy the code to the document root of the webserver (apache2 or nginx). 
- Enable php module for apache2 and fast cgi pass for the nginx. 
- Edit wp-config.php file and add database credentials in it.
- Restart nginx/ apache2 and hit ip addr or domain on the browser. .

![wpss](https://user-images.githubusercontent.com/113520851/207797922-df825db9-3af9-48d8-9992-b1f3c5b39d5c.png)








