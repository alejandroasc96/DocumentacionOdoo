# Comandos Docker


## Comandos útiles

-   docker images #para ver la lista de imágenes descargadas.

-   docker ps #para ver la lista de contenedores en ejecución.

-   docker ps -a #para ver la lista de todos los contenedores ejecutados.

-   docker rm #para borrar contenedores en nuestro equipo.

-   docker rmi #para borrar imagenes en nuestro equipo.

-   docker sear ch #para buscar imágenes en el Docker Hub.

-   docker pull #para descargar imágenes desde Docker Hub.

-   docker-compose up #lee el compose y monta los dockers

-   docker tag bb38976d03cf yourhubusername/verse_gapminder:firsttry

-   docker push yourhubusername/verse_gapminder

-   docker run -it nombreDelContenedor #para arrancar un contenedor ya creado.

-   docker stop idContenedor #para parar un contenedor ya creado.
-   docker stop $(docker ps -a -q) #para pausar todos los contenedores en funcionamiento

-   docker exec -u root -t -i nombredelamaquina /bin/bash #ejecutar maquina virtual Docker
