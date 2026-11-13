# Proyecto Capa 7 - Modelo OSI

Sitio web en HTML para la actividad práctica de internet: Redes y comunicaciones.

## Integrantes
- Maria Alejanadra Gonzalez
- Daniel Alejandro Ruiz
- Julian Fernadez Alvarez

## Cómo ejecutarlo con Docker

1. Clonar el repositorio:
   ```
   git clone https://github.com/mariaalejandragonzalez/proyecto-capa7.git
   cd proyecto-capa7
   ```
2. Construir la imagen:
   ```
   docker build -t sitio-capa7 .
   ```
3. Ejecutar el contenedor:
   ```
   docker run -d -p 8080:80 sitio-capa7
   ```
4. Abrir en el navegador: http://localhost:8080