#Crear la imagen 
docker build -t mi-app-web:latest

#Levantar el contenedor 
docker run -d -p 8080:80 --name mi-contenedor mi-app-web:latest
