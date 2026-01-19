# ispconfig directive snippet for nextcloud with nginx, tested with nextcloud 31

Here you can find a directive snippet for nextcloud with nginx in an ispconfig env.

## Subdirectory

If nextcloud is installed in a subdirectory (not subdomain) add the following to the top of the config:

*replace "nextcloud" with the folder name*
```
##subroot /nextcloud ##
[...]
```
