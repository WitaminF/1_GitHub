# Objectif 1 : configuration du dépot et utilisation de GitHub

Pour ce premier objectif : créer un dépôt git et utiliser quelques commandes afin de se familiariser avec cet outil,
effectuer quelques commit, créer les fichiers de base et travailler avec les branches.

1. Créer le dépôt Git
2. Cloner le dépôt git dans un dossier local
3. Ajouter les fichiers par défaut pour le premier commit
4. Commit
5. Push
6. Créer une branche et l'utiliser
7. Voir toutes les branches du projet
8. Push avec une branche
9. Créer pull request
10. Merge pull request
11. Changer de branche
12. Supprimer une branche

### 1. Créer le dépôt Git

````
https://github.com/WitaminF/local-ethereum-blockchain
````

### 2. Cloner le dépot git dans un dossier local

````
C:\Users\schei\OneDrive\Projets Personnel\local-ethereum-blockchain
````

### 3. Ajouter les fichiers par défaut pour le premier commit
-A pour tout ajouter

````
Git add -A
````

### 4. Commit
-m "message", pour ajouter un message au commit

````
git commit -m "first commit"
````

### 5. Push

````
git push
````

### 6. Créer un branche et l'utiliser

````
git checkout -b image
````

### 7. Voir toutes les branches du projet

````
git branch
````

### 8. Push avec la branche

````
git push origin image
````

### 9. Créer une pull request
Aller sur github, regarder les modification et créer une pull request

### 10. Merge pull request
Toujours sur github, merge la pull request de image à main

### 11. Changer la branche et revenir à la branche main
````
git checkout main
````

### 12. Supprimer une branche

````
git branch -D image
````

# Commandes Utiles
Quelques commandes utiles:

## Commit avec touts les fichiers modifiés

````
git commit -a -m "message"
````

## Cheat Sheet par From Scratch

![Cheat Sheet github](https://raw.githubusercontent.com/WitaminF/1_GitHub/main/IMG/GithubCheatSheet.png)