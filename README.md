# Recon

Instrucciones para configurar el script:
Guardar el script: Guarda el contenido del script en un archivo llamado recon (sin extensión) en tu directorio /usr/bin.

bash
sudo nano /usr/bin/recon
Pegar el contenido: Pega el contenido del script y guarda el archivo.

Dar permisos de ejecución:

bash
sudo chmod +x /usr/bin/recon
Ejecutar el script: Para usar el script, simplemente ejecuta:

bash
recon ip_victima
Este script realizará las siguientes tareas:

Identificará el TTL y el sistema operativo basado en el TTL.

Ejecutará un escaneo de puertos y servicios con Nmap.

Listará directorios con Gobuster.

Identificará tecnologías utilizadas con WhatWeb.

Guardará todos los resultados en un archivo llamado recon.txt.
