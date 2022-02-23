# ft_server

The goal was to create a functionnal web server implementing different services such as Mysql, Wordpress and phpMyAdmin, using a docker container.

You can use by doing :
-> docker build -t mdaillet .  
-> docker run -p 80:80 -p 443:443 -d mdaillet  
-> docker run --env INDEX=off -p 80:80 -p 443:443 -d mdaillet  

It will create a local wev server where you will be able to see beautiful banana pictures.
