# Creation d'un dépot GIT

##Creation d'un dépot GIT en local

Dans la consol, initialisation du dépot :

```bash
git init
```

Ceci crée un dossier caché nommé `.git` qui contient tout l'historique du projet 

## Visualisation de l'etat de GIT

```bash
git status
```
## Pour voir les fichiers et dossiers Unix

le -a permet d'afficher les fichiers cachés

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

Les fichiers en attentes de sauvegarde sont en vert, **new file** ou **modified**

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

## Pour retirer un fichier du staging

```bash
git restore --staged README.md
```

Le fichier est sorti du `staging` et sera affiché en rouge avec `git status`

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
