# apache-2.4-webdav

This is an example of a WebDAV setup that can replace a legacy FTP server for
both downloads and uploading.  It allows anonymous users to upload files to
`/incoming/`.  It shows a server status page at `/status/`.
You should modify this configuration to suit your needs.  Do not let it out
on the open Internet unless you understand the security implications.
SSL support is missing.

## Installation on Debian/Ubuntu

```sh
# Only with Rivet 3.x.
sudo a2dismod mpm_prefork
sudo a2enmod mpm_event

sudo ./deploy
```

## License

MIT.
