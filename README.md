# ft_server by mdaillet

Project from 42 school. The goal was to create a web server using different services such as Mysql and Wordpress.

You can use by :

docker build -t mdaillet .

docker run -p 80:80 -p 443:443 -d mdaillet

docker run --env INDEX=off -p 80:80 -p 443:443 -d mdaillet
