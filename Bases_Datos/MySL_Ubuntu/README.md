# Instalación de MySQL en Ubuntu

En esta práctica vamos a instalar el MySQL en una máquina Ubuntu.

- Lo primero que hay que hacer es entrar en nuestro terminal e insertar el siguiente comando.

![1](./img/1.png)

- Después de la instalación debemos averiguar la versión de nuestro MySQL. Insertamos este comando.

![2](./img/2.png)

- También debemos instalar el cliente.

![3](./img/3.png)

- El siguiente paso será reinicar el demonio `mysqld`. Para ello insertamos el comando a continuación.

![4](./img/4.png)

- Ahora probaremos la conexión de cliente a servidor de MySQL.

![5](./img/5.png)

- Después de la instalación y de monitorizar la conexión de cliente a servidor, vamos a configurar su seguridad post-instalación.

![6](./img/6.png)

- Nuestro siguiente paso es instalar el Workbench.

![7](./img/7.png)

- Nuestro siguiente paso será instalar el PHPMyAdmin sobre Apache. Lo primero es instalar el phpmyadmin.

![8](./img/8.png)

`Nos aparecerá una ventana que nos preguntará sobre instalar apache. Con la barra espaciadora aceptamos en apache.`

![9](./img/9.png)

- A lo largo de la instalación nos preguntará sobre qué puerto queremos trabajar.

![9](./img/11.png)

- El usuario.

![9](./img/12.png)

- Es importante tener iniciado el Apache como muestra la imagen.

![9](./img/13.png)

- Con estos comandos habilitamos  las extensiones PHP`mcrypt`
 y `mbstring`.

![9](./img/14.png)

- Debemos reiniciar el apache para los cambios surgidos.

![9](./img/15.png)

- Entramos en `localhost/phpmyadmin` e insertamos nuestro usuario y contraseña.

![9](./img/16.png)

- El archivo de configuración es `/etc/apache2/conf-enabled/`.

- El usuario propietario de la instalación es `mysql`.

- El proceso demonio es `mysqld`
