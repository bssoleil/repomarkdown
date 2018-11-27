# **cheat sheet terminal** #

## _les bases_ ##

- ouvrir le terminal : ctrl + alt + t
- fermer le terminal : exit 
- nettoyer le terminal : clear
- répète la dernière commande : !!
- annule : ctrl + c
- installer : sudo apt-get install
- auto completion : tab

## _permissions_ ##

- ordre : user/group/all
- types :   
 - r : lire  
 - w : ecrire  
 - x : executer  
- modifier les permissions : chmod

## _répertoire_ ##

- montre le répertoire actuel (montre où on est)
- créer un répertoire (dossier) : mkdir
- se déplacer dans un dossier : cd nom du dossier
- aller dans le répertoire précédent : cd .. ou cd-  

## _fichiers_ ##

- créer un fichier : touch nom.format
- lister les fichiers : ls
- lister les fichiers et les fichiers cachés : ls -a
- lister les fichiers et les droits : ls -lh
- lister les fichiers (cachés) et les droits : ls -la  

## _déplacement/renommer/supprimer_ ##

- déplacer un fichier vers un dosssier :mv nom.format document/
- déplacer un dossier dans un dossier: mv dossier 1 dossier 2
- renommer un fichier : mv anciennom.format nouveaunom.format
- supprimer un fichier : rm nom
- Supprimer un fichier avec une demande de confirmation : rm -i nom
- Supprimer un fichier fichier sans confirmation : rm -f nom
- Supprimer un dossier vide : rmdir nom
- Supprimer un dossier et son contenu : 	rm -r nom  


# _cheatsheetvim.md_ #  


## _Commandes de base_ ##


- Passer dans le mode insertion : i
- Ajouter en fin de ligne : A
- Quitter : :q
- Quitter sans enregistrer : :q!
- Enregistrer le fichier : :w
- Enregistrer et quitter : :wq
- Enregistrer (seulement en cas de modification) et quitter : :x
- Passer en mode "collage" : :set paste  

## _commandes d'édition_ ##  

- Annuler la dernière opération: u
- Rétablir la dernière opération annulée : <control>-r
- Répéter la dernière opération d'édition : .
- Copier la ligne (4yy = 4 lignes) : yy
- Couper la ligne (4dd = 4 lignes) : dd
- Coller après (P = insérer avant) : p
- Effacer le caractère : x
- Effacer le texte jusqu'à la fin du mot : dw
- diw 	Effacer le mot sous le curseur : diw  

## _Recherche / remplacement_ ##  

Rechercher du texte : /
Rechercher l'occurence suivante :n
Rechercher l'occurence précédente : N
Remplacer le texte jusqu'à la fin du mot : cw
Remplacer le mot : ciw
Remplacer jusqu'en fin de ligne :c
 Répéter la dernière opération d'édition : .
Remplacer tous (g) les A par des B : :%s/A/B/g  

# _cheatsheetgit.md_ #  

## _Installation_ ##  

- Pour vérifier si on a installé Git dans le Terminal, tapez : git –version
-  Créer un nouveau projet et initialiser Git :  

- Créer un nouveau dossier : mkdir nomdudossier
- cd nomdudossier
- git init
- git status
- Ouvrir le dossier et créer un nouveau fichier, puis ajouter un peu de contenu : 
- Créer un nouveau ficher : touch nomdufichier

 



