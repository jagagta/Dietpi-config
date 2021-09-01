# Usb configuration
  add Qbittorent user write access to the usb location

dietpi@DietPi:/mnt/usb/torrent_downloads/temp $ sudo chown -R qbittorrent /mnt/usb/torrent_downloads/
dietpi@DietPi:/mnt/usb/torrent_downloads/temp $ ls -la /mnt/usb/
total 28
drwxrwsr-x 4 dietpi      dietpi  4096 Sep  1 08:55 .
drwxr-xr-x 8 root        root    4096 Aug  4 19:29 ..
drwx------ 2 dietpi      dietpi 16384 Sep  1 08:53 lost+found
drwxrwxrwx 3 qbittorrent dietpi  4096 Sep  1 08:55 torrent_downloads
