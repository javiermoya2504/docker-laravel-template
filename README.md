# Plantilla Laravel 11 Dockerizada

Os propociono una plantilla realizada con Laravel 11 y Docker para vuestros proyectos y poder tenerlo todo desde el principio.

## Tecnologías Utilizadas

### - Apache
### - PHP 8
### - Mysql

# Iniciación del proyecto 

Se dispone de un fichero Makefile con las siguientes instrucciones

## make start

Comando principal que va a permitir generar todo el contenedor desde cero de la plantilla. Esto hará que se elimine los contenedores creados anteriormente para crearlo todo desde cero.

## make stop

Comando que sirve para parar la ejecución de los contenedores

## make composer-install

Comando que sirve para instalar las dependencias del proyecto. 

Se ejecuta en caso de que sea necesario actualizar las dependencias.

## make bash

Comando que permite acceder al bash dentro del contenedor para poder ejecutar las distintas instrucciones que puedan a afectar al funcionamiento del contenendor.

Por ejemplo: Los comandos que se deben de ejecutar de Laravel para migraciones.


