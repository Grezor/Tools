 - [lien1](https://guillaumebriday.fr/comment-jutilise-git-mes-astuces-et-bonnes-pratiques)

```bash
# lister toute les branches remote
> git branch -r
# ensuite, on peux taper cette commande
> git checkout -b LocalName origin/remotebranchname
# ignore les fichiers modifier 
> git checkout .
# Afficher l'historique des commit
> git log
# afficher l'historique sous forme oneline 
# exemple => [numero_commit] [nom du commit]
> git log --pretty=oneline
> git log --pretty=short

# commit abcdefghij...
# Author: Name <Name>
# Commit: Name <Name>
# Name commit
> git log --pretty=full 


```
