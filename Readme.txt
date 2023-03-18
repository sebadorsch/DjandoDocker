Pasos para Dockerizar una aplicacion Django

1: Seleccionar la imagen de Docker a usar
2: Copiar los archivos necesarios para poder preparar el equipo
3: Instalar los programas necesarios y actualizar programas para poder correr la aplicacion
4: Copiar los archivos del proyecto
5: Ejecutar el proyecto



docker build [OPTIONS] PATH | URL | -
docker build -t djangodocker .


docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
docker run -p 8000:8000 djangodocker


enter:
    docker exec -it {container_id}



usefull commands:
    docker ps
    docker stop {container_id}