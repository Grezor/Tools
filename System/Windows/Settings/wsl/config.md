# wsl

https://ostechnix.com/how-to-switch-between-multiple-php-versions-in-ubuntu/

```bash
# version installée par défault
php -v
# Passer de PHP 7.x à PHP 5.x
sudo a2dismod php7.2
# output
Module php7.2 disabled.
To activate the new configuration, you need to run:
systemctl restart apache2
# Ensuite, activez le module PHP 5.6
sudo a2enmod php5.6
# Définissez PHP 5.6 comme version par défaut à l'aide de la commande :
$ sudo update-alternatives --set php /usr/bin/php5.6
# Vous pouvez également exécuter la commande suivante pour définir la version système de PHP que vous souhaitez utiliser par défaut.
sudo update-alternatives --config php
```