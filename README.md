# Home File Server
### Torent - Deluge. 
Available at http://{host}:8112

Image used - https://registry.hub.docker.com/r/linuxserver/deluge

### Samba
Available at smb://{host}/storage

Image used - https://hub.docker.com/r/sixeyed/samba/

### Plex Media Server
Available at http://{host}:32400/web

Image used - https://hub.docker.com/r/linuxserver/plex/

### Calibre Library Server
Available at http://{host}:8080/

Reading available at http://{host}:8081/

Image used - https://hub.docker.com/r/linuxserver/calibre/

##
### First run:
```shell script
sudo docker-compose up --build -d
```
## In the plans:
* FTP 
* Some Cloud
* Telegramer https://github.com/noam09/deluge-telegramer
* Torrent Monitor https://github.com/nawa/torrentmonitor-dockerized