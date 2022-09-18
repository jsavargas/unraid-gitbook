---
description: Descargar usando Sonarr/Radarr
---

# Sonarr/Radarr \[Work In Progress]

![](<../.gitbook/assets/image (2).png>)

En este tutorial se tratará de explicar el correcto funcionamiento de Sonarr/Radarr para automatizar las descargas de nuestras series y películas usando las plantillas de Unraid.

Usaremos los contenedores de Linuxserver:

* qbittorrent (cualquier cliente torrent sirve, en este caso usaremos qbittorrent)
* Sonarr
* Radarr
* Plex/Jellyfin

![](<../.gitbook/assets/image (31).png>)![](<../.gitbook/assets/image (15).png>)![](<../.gitbook/assets/image (11).png>)![](<../.gitbook/assets/image (19).png>)

## Rutas principales: <a href="#definiremos-dos-rutas-principales" id="definiremos-dos-rutas-principales"></a>



Definiremos dos rutas principales:

* **/mnt/user/multimedia** : Carpeta de multimedia (Series y Películas)
* **/mnt/user/download** : Carpeta de descargas (torrent)

Estas rutas no son obligatorias, ustedes pueden usar las que mas les acomoden

![](<../.gitbook/assets/image (25).png>)

## qbittorrent <a href="#qbittorrent" id="qbittorrent"></a>

Instalaremos el contenedor del cliente torrent que utilizaremos

![](<../.gitbook/assets/image (1).png>)

Seleccionaremos la opcion "Default"

![](<../.gitbook/assets/image (16).png>)

y asignaremos la ruta correspondiente a las descargas

![](<../.gitbook/assets/image (21).png>)

Aplicamos los cambios y comienza la instalación

![](<../.gitbook/assets/image (4).png>)
