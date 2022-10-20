# Pila-Lamp-en-dos-niveles

#Configuracion de la maquina de mysql
Creo el usuario
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/1.png)

Clono el repositorio de git
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/2.png)

Borro esas líneas para que no de problemas al importar la base de datos
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/3.png)

Importo la base de datos
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/4.png)

Cambio la ip del archivo 50-server.cnf que se encuentra en /etc/mysql/mariadb.conf.d
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/5.png)

Volvemos a entrar con el root en mysql para darle todos los permisos de la base de datos al usuario
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/6.png)

#Configuracion de la maquina de apache
Entramos con la maquina de apache nos situamos en /var/www y creamos la carpeta de la pagina web. Clonamos el repositorio de git y movemos el contenido de la carpeta src a la carpeta de la pagina
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/7.png)

Creo el nuevo archivo de configuración de la paginaweb y le cambio la ruta a la carpeta creada anteriormente
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/8.png)
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/9.png)

Despues deshabilitamos la conficuracion que viene por defecto y activamos la nueva configuración. (Guarde la configuración sin el punto conf y tuve que guardala de nuevo). Por ultimo recargamos apache2 para guardar todos los cambios
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/10.png)

En el archivo config.php cambiamos localhost por la ip de la maquina mysql
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/11.png)
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/12.png)

Al entra con la ip en un navegador me sigue dando el mismo problema que me daba en clase
![](https://raw.githubusercontent.com/raulqlda/Pila-Lamp-en-dos-niveles/main/capturas/13.png)
