# Installation on Debian/Ubuntu

```sh
sudo a2enmod macro

sudo a2enmod dav
sudo a2enmod dav_fs
sudo a2enmod dav_lock

sudo a2enmod rivet
sudo a2enmod cache
sudo a2enmod cache_disk

# Only with Rivet 3.x.
sudo a2dismod mpm_prefork
sudo a2enmod mpm_event

sudo ./deploy
```
