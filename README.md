## compose-overrides.yaml

Place in IOT Stack directory, run `menu.sh` to merge then `docker-compose up -d`.

## fstab.nas-automount

Add content to `/etc/fstab` to mount nas footage directory when opening the mount point. motioneye container `footage` volume expects this mount point to exist.
