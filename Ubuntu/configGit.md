# configuration de git sur Ubuntu : 
```bash
$ git --version
# output
git version 2.25.1

# mettre les packages a jour :
$ sudo apt update
# une fois la mise a jour terminée
$ sudo apt install libz-dev libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext cmake gcc

# créez un répertoire temporaire
$ mkdir tmp
# rentrer dans le dossier
$ cd /tmp

# la version la plus récente
$ curl -o git.tar.gz https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.26.2.tar.gz

# décompressez le fichier
$ tar -zxf git.tar.gz

# déplacer vous dans le nouveau repertoire
$ cd git-$

# créer le paquet et l'installer
$ make prefix=/usr/local all
$ sudo make prefix=/usr/local install
$ exec bash

# une fois terminé 
$ git --version
# Output
git version 2.26.2
```