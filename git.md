## Git

- Versionning

  - sauvegarder les versions , chronologie
  - permet de revnir en arrière
  - synchronisation
  - collaboratif
  - branches

- Utilisation

  - ligne de commande
  - plugin VSC
  - outils bureautque : Github Desktop , TortoiseGit

- Interpreteur de commande :

  - mac : zsh , bash ,

- Invite de commande : configuration système

```
  >
  $
  PATH
  alias

```

## Rappel de commandes

- git config --global user.name "Dan Arki"
- git config --global user.email danarki6@gmail.com

- git --version : appeler git

---

- pwd : savoir ou on se trouve

---

- cd : change directory (changer de dossier)

---

- mkdir : make directory (créer un dossier)

---

- cd .. : remonter d'un cran

---

- ls : list directory (lister les dossiers/fichiers)

---

- tree : voir l'arborescence

---

- `dir >toto.txt` : rediriger la sortie vers un fichier

---

- man ... : explication d'une commande
  - :q pour quitter le manuel

---

- clear : vider le terminal

## Commencer un projet dans Git

```sh
git init . (les fichiers sont en U)
# U = untrack

git add readme.md (les fichiers sont en A)
# A = added


#valider = commit
git commit -am"Premier commit" (disparition du A et est alors valider)

# Lorsqu'on modifie le fichier  comit
# M = modify

git diff (voir la différence de ce qui a ete modifier)


et donc refaire un commit lors de chaque changement majeur -> git commit -am"Deuxieme commit"

# Créer .gitignore
# - fichiers avec identifiants et mots de passe
# - dossiers temporaires , dossiers dépendances , dossiers de compilation ...

git add . (ajouter tout les dossiers)

on commit encore vu que l on vient de tout rajouter
git commit -am"Ajout du .gitignore et de tout le reste"

#créer le dépot sur GitHub

git remote add origin 


```
