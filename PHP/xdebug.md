## installation de xdebug : 
```ini
site officiel : https://xdebug.org/
```

- placer le fichier dans le **dossier ext**
    - avec comme nom : ```php_xdebug.dll```
- retourner dans le dossier php.ini

```ini
[xdebug]
zend_extension=xdebug
xdebug.start_with_request=yes
xdebug.client_host=127.0.0.1
xdebug.client_port=9000
xdebug.discover_client_host=1
xdebug.mode=debug
xdebug.remote_handler=dbgp
extension_dir = "ext"
```