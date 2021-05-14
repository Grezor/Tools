## Pour mettre a jour composer dans Laragon : 
- l'application laragon
- puis dans le terminal taper composer -V
- Aller sur le site de composer 
  - taper ceci dan le terminal 
  - ce rendre dans le path **c:\laragon\bin\composer**
  - taper les commandes ci-joint
```sh
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '756890a4488ce9024fc62c56153228907f1545c228516cbf63f885e036d37e9a59d27d63f46af1d4d07ee0f76181c7d3') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

