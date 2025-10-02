## Kays Documentation of Project 2

`sudo apt update`

`sudo apt install nginx`

`sudo systemctl status nginx`

![nginx-status](./images/nginx-status.PNG)

*First, let us try to check how we can access it locally in our Ubuntu shell, run:*

`curl http://localhost:80`

OR

`curl http://127.0.0.1:80`

*Open a web browser of your choice and try to access the following url*


`http://<Public-IP-Address>:80`

OR

`curl -s http://169.254.169.254/latest/meta-data/public-ipv4`




### INSTALLING MYSQL

`$ sudo apt install mysql-server`

*When the installation is finished, log in to the MySQL console by typing:*

` sudo mysql`



