## Instructions for Dockerfile:

// Comando para hacer la imagen

docker build -t docker-express .

// Comando para correr el contenedor y darle nombre, tambien indicandole el puerto 

docker run -d --name=Dylan-express -p 4444:3000 docker-express