This is a theme for Plesk 11.5. Following paths are valid on a Linux server.

## Modify

1. Fork this repo and edit the CSS and images as needed.

## Install

1. Compress all the files into a zip.
2. Upload it to your server using FTP (or any other file transfer method).
3. Connect to your server through SSH.
4. Use this command to install the skin.

```
/usr/local/psa/bin/branding_theme -i -vendor admin -source <path/to/file.zip>
```


## Donwload back

1. Connect to your server through SSH.
3. Use this command to package the skin.

```
/usr/local/psa/bin/branding_theme -p -name jmcouillard -destination <path/to/accessible/location>
```

## Online editing

Themes are located here, so you may editi it live to see what is happening, and then download it for backup purposes.

```
/usr/local/psa/admin/htdocs/theme-skins/jmcouillard
```