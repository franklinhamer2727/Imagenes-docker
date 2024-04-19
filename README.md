# Imagenes-docker
## Comandos para ejecutar Docker-Compose
Link de ingreso:
### POSTGRES
http://localhost:5050/browser/
- usuario: admin@admin.com
  - contraseña: root

    Procede a ingresar el comando de `docker inspect <CONTAINER ID>`
      - Aparecera la ip donde se esta ejecutando el contenedor es una dato mimportante al ingresar  el servidor a travez de pgadmin
### MONGO
ejecuta el comando 
docker compose up -d
verificacion de la red
docker network ls
ingresa al link http://localhost:8081
- usuario: admin
- contraseña: pass

### SQLServer
Ejecuta el siguiente comando en el terminal `docker compose up -d`
- Ejecuta los siguiente para opetener la ip `docker inspect <CONTAINER ID>`
- Ingresa a DBeaver e ingresa 
  - usuario: sa
  - contraseña: My_secret_p@ssword
  - puerto: 1234