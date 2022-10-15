# torrent-automagico
## Simplemente containers con docker con 
- Plex
- Addarr
- Sonarr
- Radarr
- Jackett
- transmission
- smb

Cada container hace su trabajo
Plex es el centro multimedia
Addarr es un python que se comunica con jackett para bajar, usando transmission, torrent misc
Sonarr y Raddarr bajan series y peliculas comunicandose con jackettm, y usando transmission
smb para compartir algunos objetos en la lan
Transmission es un cliente de torrents
