# Transmission.bundle

For Setup this Transmission plugin on a Debian Plex Media Server (up to date with plexpass on 23/10/2015)

root@debian-streaming:/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins# git clone https://github.com/thingsinjars/Transmission.bundle.git

Clonage dans 'Transmission.bundle'...
remote: Counting objects: 301, done.
remote: Total 301 (delta 0), reused 0 (delta 0), pack-reused 301
Réception d'objets: 100% (301/301), 3.64 MiB | 2.04 MiB/s, fait.
Résolution des deltas: 100% (39/39), fait.
Vérification de la connectivité... fait.

root@debian-streaming:/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins# ls
SiteConfigurations.bundle  Transmission.bundle  WebManager.bundle

root@debian-streaming:/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins# cd Transmission.bundle/

root@debian-streaming:/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins/Transmission.bundle# ls
Contents

root@debian-streaming:/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins/Transmission.bundle# service plexmediaserver restart
