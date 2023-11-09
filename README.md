## Instructions for Dockerfile:

docker build -t docker-express .

docker run -d --name=Dylan-express -p 4444:3000 docker-express

// Comando para correr el contenedor y darle nombre, tambien indicandole el puerto 