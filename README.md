Fork from https://github.com/vSense/docker-plex

Juste revu pour autoriser le resau local de base


docker run --name=plex -d -v /data/settings/plex:/config -v /data/media:/library -p 32400:32400 justtolaunch/plex-lan
