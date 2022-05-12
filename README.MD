comandos usados:

1-docker run -d  --name devtest  -v myvol2:/app  monta un contenedor con un volumen  y corra como demonio
2-docker images muestra las imanges
3-docker ps muestra los procesos activos de docker
4-docker pull descarga una imagen 
5-docker exec -it  id /bin/bash para entrar a la maquina en si
6-docker volume create nombre para crear un volumen


Para lanzar la imagen simplemente hay que crear el volumen con el comando nº 6 dandole un nombre
y depues ejecutar el comando 1 pasandole el nombre del volumen creado,el dockerfile se encargade hacer el copy de mi index html que tambien está en el repo
