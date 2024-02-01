# GIT

## Outil collaboratif de versionning

### Configuration

A faire une fois par machine

- git config --global user.name "nom à choisir"

- git config --global user.email "adresse mail du compte github"

- git config --global push.default simple (il poussera toutes les branches vers la branche distante et les fusionnera. Si vous ne voulez pas pousser toutes les branches, vous pouvez pousser la branche actuelle si vous spécifiez entièrement son nom, mais ce n’est pas très différent de default.)

- git config --global color.ui true (pour une meilleure lecture)

- git config --global pull.rebase true (permet moins de merge)

### LDC
- git clone + url à récupérer sur le repo github (https ou ssh)

- git remote add origin + ("notre url donnée par github") (demande à git d'ajouter un serveur distant pour envoyer nos données)

- git push -u origin master (pour le paramétrage, à faire qu'une fois ! Pousse notre contenu dans notre serveur distant. La branche master est paramétrée pour suivre la branche master distante depuis origin.)

- git init (initialise le dossier où on se trouve pour GIT)

- git status (pour vérifier si on a des fichiers modifiés non pris en compte)

- git add "nom du fichier" (ajouter un fichier à git)

- git add . (ajoute tous les fichiers à git)

- git commit -m "nom du commit" (créer un commit avec le nom qu'on lui a donné)

- git log (donne la liste de tous nos commits (de nos modifications ajoutées))

- git log --oneline (affiche nos commits plus clairement)

- git push (pousse tout nos commits vers notre serveur distant de github)

- git pull (permet de récupérer les changements effectués par un autre user) !! A FAIRE ABSOLUMENT AVANT UN NOUVEAU PUSH !!

- git remote set-url origin (changer l'origine du push après le clonage. Url à prendre dans le repo github)

### Divers

- .gitignore (à mettre à la fin d'un fichier ou d'un dossier pour le cacher dans le repo lors du push)

- .keep (rends visible un dossier vide par exemple)
