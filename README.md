# Home File Server
### Torent - Deluge. 
Available at http://{host}:8112

Image used - https://registry.hub.docker.com/r/linuxserver/deluge

### Samba
Available at smb://{host}/storage

Image used - https://hub.docker.com/r/sixeyed/samba/
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