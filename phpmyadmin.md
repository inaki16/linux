
# Instalación phpmyadmin en ubuntu desktop 18



Instalación phpmyadmin en ubuntu desktop, incluyendo mysql-server, apache2 y php.


# Instalacion mysql-server
~~~
sudo apt install mysql-server     
sudo mysql
		mysql> CREATE USER 'usuario'@'localhost' IDENTIFIED BY 'password';   
		mysql> GRANT ALL PRIVILEGES ON *.* TO 'usuario'@'localhost' WITH GRANT OPTION;   
		mysql> exit
~~~      

instalamos mysql y creamos un usuario con acceso a todas las bases de datos desde localhost.  

## Instalación phpmyadmin
~~~
sudo apt install apache2
sudo apt install phpmyadmin  
~~~
Instala automáticamente  phpmyadmin, mysql-server, apache2 y php.    

en http://localhost/phpmyadmin tenemos la web de phpmyadmin, debemos utilizar el usuario y password creado anteriormente.    








https://www.digitalocean.com/community/tutorials/como-instalar-mysql-en-ubuntu-18-04-es.   

 

