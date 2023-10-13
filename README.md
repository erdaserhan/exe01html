# Creation d'un dépot GIT

##Creation d'un dépot GIT en local

Dans la consol, initialisation du dépot :

```bash
git init
```
## Visualisation de l'etat de GIT

```bash
git status
```
## Pour voir les fichiers et dossiers Unix

```bash
ls -a
```

## Pour ajouter un fichier à la future sauvegarde

```bash
git add README.md
```

## Pour ajouter un fichier à la future sauvegarde

```bash
git add README.md
```
## Pour effectuer la sauvegarde

Les fichiers en attentes de sauvegarde sont en vert

Les fichiers non suivi sont en rouge.

Seul les fichiers en **staging** seront sauvés

```bash
git commit -m"Message du commit"
```


Un commit est une sauvegarde, on peut y accèder 
avec un `git log` (affichage des identifiants de sauvegardes et `git show` ( sans paramètre, affichage du derniere commit

## Pour ajouter tout les fichiers en staging 

```bash
git add .
```

## Ajout d'un serveur 

Nous allons utiliser un dépot que l'on va créer sur github.com,
aorès connexion. Comme c'est un travail personnel, son URL sera de ce type https:https://github.com/VOTRE_USERNAME/leNomDuProjet

Nous créons un new Repository, puis copions la clefs SSH :

git@github.com:erdaserhan/exe01html.git

Nous retournons dans notre console :

```bash
git remote add origin git@github.com:erdaserhan/exe01html.git
```

Pour voir si ca a fonctionné :

```bash
git remote -v
```
