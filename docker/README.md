#Docker
## Crear la imagen de docker
´´´ bash
docker build -t api_rest:10.06.22
´´´
## crear un contenedor 

´´´ bash 
docker run -it -v "$PWD"/home:/home/code --net host --katia api_rest -h api_rest api_rest:10.06.22