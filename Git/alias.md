## les Alias : 
Le terme alias est synonyme de raccourci. Les alias permettent de créer des commandes plus courtes mappées sur la commandes plus longues. Les alias permettent des raccourcis de travail plus efficaces en nécessitant moins de frappes au clavier pour exécuter une commande. 

Par exemple ```git checkout ```, la commande checkout est une commande git fréquemment utilisée, qui s'ajoute aux frappes cumulées dans le temps. Je le vais donc modifier le fichier gitconfig et crée une commande ```git co ``` et me permet de donc d'économiser une précieuse puissance au bout des doigts. 

```
[alias]
	co = checkout
	cob = checkout -b
	coo = !git fetch && git checkout
	br = branch
	brd = branch -d
	brD = branch -D
	
	st = status
	aa = add -A .
	cm = commit -m
	aacm = !git add -A . && git commit -m
	cp = cherry-pick
	amend = commit --amend -m
	dev = !git checkout dev && git pull origin dev
	staging = !git checkout staging && git pull origin staging
	master = !git checkout master && git pull origin 
	po = push origin
	pod = push origin dev
	pos = push origin staging
	pom = push origin master
	poh = push origin HEAD

	plo = pull origin
	plod = pull origin dev
	plos = pull origin staging
	plom = pull origin master
	ploh = pull origin HEAD
	```