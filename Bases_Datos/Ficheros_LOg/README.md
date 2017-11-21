# Ficheros LOG

### Error LOG

![](./img/1.png)

* Los ficheros LOG son problemas encontrados arrancando, trabajando o parando mysqld. Información sacada de https://dev.mysql.com/doc/refman/5.7/en/server-logs.html

* El archivo cnf y los archivos log se almacenan en esta dirección.

![](./img/2.png)

* En el momento en que cerramos forzosamente el servicio vemos que los archivos log siguen iguales.

* El comando `perror` muestra por pantalla una descripción para un error de código de sistema. Información sacada de https://dev.mysql.com/doc/refman/5.7/en/perror.html

### General Query LOG

![](./img/3.png)

* El **General Query Log** establece conexiones de cliente e información recibida de los clientes. Información sacada de https://dev.mysql.com/doc/refman/5.7/en/server-logs.html

* Comprobamos el funcionamiento de los errores.

![](./img/4.png)

* Accediendo al fichero de los logs dentro del Workbench en `Server Logs` podemos observar las últimas conexiones y consultas realizadas.

![](./img/5.png)

* Desde el servidor podemos observar que hay más archivos de error que el cliente.

![](./img/6.png)
