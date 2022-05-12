comandos usados:

docker run -d  --name devtest  -v myvol2:/app  monta un contenedor con un volumen  y corra como demonio
docker images muestra las imanges
docker ps muestra los procesos activos de docker
docker pull descarga una imagen 
docker exec -it  id /bin/bash para entrar a la maquina en si
docker volume create nombre para crear un volumen