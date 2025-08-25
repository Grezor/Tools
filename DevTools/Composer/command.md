# Composer : 
[lien de telechargement](https://getcomposer.org/download/)

## Command : 
```bash
# savoir la version 
> composer -V
Composer version 2.0.13 2021-04-27 13:11:08
```

```bash
# Permet de mettre les paquets à jour
> composer update
```

```bash
# mettre a jour
> composer self-update
You are already using the latest available Composer version 2.1.3 (stable channel).
```

```bash
# initialiser composer dans un projet
> composer init

# name :  il s'agit du nom du package.
# description:  Une brève description du package.
# author :  le nom du propriétaire du package.
# type :  Définit le type de package.
# page d'accueil :  URL de la page d'accueil du package.
# require :  certains packages nécessitent une contrainte de version. Il doit être au format « proj/paa:1.0.0 »
# require-dev : packages requis pour le développement
# stabilité (-s) :  une valeur pour le champ de stabilité minimale.
# license (-l) :  Le type de licence du package.
# référentiel :  où peut se trouver le package. Un référentiel spécifie où un package est hébergé.
```

```bash
# permet de lister les paquets installés sur votre projet
> composer show
```

```bash
# Permet de lister les paquets obsolètes et qui auraient besoin d’une mise à jour (si possible, à adapter selon votre cas).
> composer outdated
```

Infos : a chaque changement de version de php, il faut relancer composer executable