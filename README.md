# GIT

## Outil collaboratif de versioning

### LDC

- git init : initialise le dossier où on se trouve pour GIT

-git status : pour vérifier si on a des fichiers modifiés non pris en compte

- git add "nom du fichier" : ajouter un fichier à git

- git add "nom du dossier"/* : ajouter un dossier complet à git

- git add . : ajoute tous les fichiers à git

- git commit -m "nom du commit" : créer un commit avec le nom qu'on lui a donné

- git log : donne la liste de tous nos commits (de nos modifications ajoutées)

- git log --oneline : affiche nos commits plus clairement

- git push : pousse tout nos commits vers notre serveur distant (github)

### Configuration

#### A faire une fois par machine

- git config --global user.name

-git config --global user.email

- git config --global push.default simple

- git config --global color.ui true

- git remote add origin ("notre url donnée par github") : demande à git d'ajouter un serveur distant pour envoyer nos données

- git push -u origin master : pousse notre contenu dans notre serveur distant. A faire une fois pour chaque nouveau repo
