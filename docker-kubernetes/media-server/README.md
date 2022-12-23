# My media server configuration

 - Jellyfin - view tv shows and movies
 
 #### All next container needed for automaic download in it))))) :
+ QBittorrent - torrent files downloading

- Jackket - search torrent in a few trackers
- JaccketSync - automatic add trackers in Sonarr, Radarr, Lidarr

+ Sonnar - follow serials, and automatic download
+ Radarr - follow movies
+ Lidarr - foolow music
+ Readarr - follow books

- FlareResolver - for jackket, entering in trackers behind cloudflare
- Torproxy - many trackers, Sonarr, Readarr not working in Russia, i use proxy:
Proxy URL: torproxy
Proxy port: 8118


## Important: *arr containers using hardlinks in filesystem, mount point *arr apps must be parent of torrent mount point!!!!