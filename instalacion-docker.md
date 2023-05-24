![Header](ryder_isologotipos.png)

***

# PIS - Instalación por Docker

> #### ⚠️ Prerequisitos
> 
> Este entorno virtual requiere de:
> - [Docker](https://docs.docker.com/engine/install/_) y (docker) compose (que en las nuevas versiones ya viene en la instalación de docker)

En primer lugar, descargar este repositorio

En el mismo encontraras el siguiente [docker-compose.yml](docker-compose.yml)

Para comenzar, simplemente correr `docker compose up` para descargar las imagenes, crear y correr los containers. Luego se puede acceder a la web desde [https://localhost:5000](https://localhost:5000)

Este comando correrá los cuatro contenedores de docker necesarios para el funcionamiento del sistema. Para verlos `docker ps`

Para conocer el uso y los límites de recursos de los contenedores utilizar el comando `docker stats`

Dejamos algunos comandos utiles y su descripción

```bash
# Levantar servicios. Se puede detener si se hace Ctrl+C
$ docker-compose up

# Si los containers siguen corriendo y se quieren detener:
$ docker-compose stop

# Si se quiere eliminar solo los containers
$ docker-compose rm

# Si se quiere eliminar todo lo que el comando "up" inicializo (containers, volumenes, imagenes, etc)
$ docker-compose down
```

