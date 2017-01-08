Plex Media Server
===========

Fork from https://github.com/vSense/docker-plex that allow trafic from 192.168.0.*

# Running

  docker run --name=plex -d -v /data/settings/plex:/config -v /data/media:/library -p 32400:32400 justtolaunch/plex-lan
