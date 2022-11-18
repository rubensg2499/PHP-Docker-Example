# PHP-Docker-Example
Este es un pequeño ejemplo de cómo usar Docker con PHP

## Construir la imagen
´sudo docker build -t my-php-web-app:1.0.0´
## Ejecutar la imagen
´sudo docker run -p 80:80 --rm -it --name my-php-web-app my-php-web-app:1.0.0s´