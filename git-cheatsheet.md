 # _cheatsheetgit.md_   
  
  ## _Installation_   
  
   - Pour vérifier si on a installé Git dans le Terminal, tapez :` git –version`

  ## _Créer un nouveau projet et initialiser Git_:
   
+ `git init` : pour créer un nouveau dépôt GIT
+ `git status` : affiche la liste des fichiers modifiés ainsi que les fichiers qui doivent encore être ajoutés ou validés
+ `git add nomdufichier`: pour ajouter des fichiers à l'index
+ `git commit -m « Nommez les changements apportés »` (ne pas oublier les « . »!)

	
+ `git diff` (indication sur les changement apportés)h

+ `git log` : Pour voir les différentes modifications apportées, son auteur, la date et le nom de la branche. 

+ `Git push` : Un simple push envoie les modifications locales apportées à la branche principale associée :
+ `git push origin master`
+ `Git checkout` :  pour créer des branches ou pour basculer entre elles.
+ `git checkout -b <nom-branche>`
+ `git checkout <nom-branche>` : Pour passer simplement d’une branche à une autre
+ `git remote`: permet à un utilisateur de se connecter à un dépôt distant.
+ `git remote –v` :  répertorie les dépôts distants actuellement configurés
+ `git branch` : peut être utilisée pour répertorier, créer ou supprimer des branches.
+ `git branch –d <nom-branche>` : Pour supprimer une branche
+ `git pull` : Pour fusionner toutes les modifications présentes sur le dépôt distant dans le répertoire de travail local
+ `git merge <nom-branche>`: est utilisée pour fusionner une branche dans la branche active
+ `git diff` : permet de lister les conflits
+ `git diff --base <nom-fichier>` :  Pour visualiser les conflits d’un fichier
+ `Git fetch` : permet à un utilisateur d’extraire tous les fichiers du dépôt distant qui ne sont pas actuellement dans le répertoire                   de travail local.  
+ `git rebase master` : utilisée pour la réapplication des commits sur une autre branche.  
