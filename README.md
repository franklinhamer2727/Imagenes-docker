
# Imágenes Docker

Este documento proporciona información sobre cómo ejecutar diferentes contenedores Docker, incluyendo PostgreSQL, MongoDB y SQL Server. Se detallan los comandos necesarios para levantar los servicios, así como los accesos y credenciales para interactuar con las bases de datos a través de herramientas como pgAdmin, Mongo Express y DBeaver.


## Indice

    Comandos para ejecutar Docker-Compose
    POSTGRES
    MONGO
    SQLServer
## Comandos para ejecutar Docker-Compose
POSTGRES

http://localhost:5050/browser/

    usuario: admin@admin.com
    contraseña: root


Procede a ingresar el comando de `docker inspect <CONTAINER ID>`. 
Aparecerá la IP donde se está ejecutando el contenedor, este es un dato importante al ingresar el servidor a través de pgadmin.

MONGO

Ejecuta el comando `docker compose up -d`. Verifica la red con `docker network ls` e ingresa al link `http://localhost:8081.`

    usuario: admin
    contraseña: pass


SQLServer

Ejecuta el siguiente comando en el terminal `docker compose up -d.`

Ejecuta los siguientes pasos para obtener la IP:

    docker inspect <CONTAINER ID>
    Ingresa a DBeaver e ingresa:
        usuario: sa
        contraseña: My_secret_p@ssword
        puerto: 1234


