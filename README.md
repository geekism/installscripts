# installscripts
Installers i write for software i use for CentOS 6

# Install nano-3.2 (CentOS 6)

```sh
wget -O- https://raw.githubusercontent.com/geekism/installscripts/master/install_nano32 | bash -
```

# Install PlexMediaServer (Current Version) (Debian/Ubuntu/CentOS)

```sh
wget -OgetPlex https://raw.githubusercontent.com/geekism/installscripts/master/install_plex | bash -
```

Crontab Entry:
Enter this as root. Or give user sudo access.
```sh
@daily sh -c 'cd /home/username/bin/ && wget -1OgetPlex https://raw.githubusercontent.com/geekism/installscripts/master/install_plex | bash getPlex >/dev/null 2>&1'
```
