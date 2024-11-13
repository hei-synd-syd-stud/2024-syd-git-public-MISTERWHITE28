# Answers of steeve blanc MISTERWHITE28

## Basics
### Task 1
On trouve le initial commit (on a ajouté deux fichiers answers.md et gitgraph.svg)
Et on peut voir qu'on est a jour et qu'on a aucun changement à commit

### Task 2
Pas de changement dans le online car on a pas encore commit mais on voit dans le stage qu'il y a un changement qui a été réalisé

### Task 3
On a réalisé le commit donc le statut (stage) voit plus de changement a commit 

### Task 4
Je m'aperçoit qu'un changement dans le fichier README.md a été réalisé et je m'aperçoit le texte qui a été ajouté, il est en vert 

### Task 5
1. Cette chaîne correspond à un identifiant de commit abrégé (appelé hash). Chaque commit dans Git reçoit un identifiant unique. Le hash complet est généralement beaucoup plus long, mais la version abrégée (7 caractères ici) suffit souvent pour identifier le commit.

2. HEAD : Il s'agit d'un pointeur qui indique la position actuelle de votre dépôt Git. Il pointe vers le dernier commit de la branche active sur laquelle vous travaillez.
main : Cela représente la branche actuelle sur laquelle vous êtes. Par défaut, la branche principale d'un dépôt Git s'appelle souvent main (anciennement master dans les versions plus anciennes). Cela signifie que votre commit 3625f8e est le dernier commit de cette branche main.

3. Ce qui suit le hash (et les éventuels marquages de branche comme (HEAD -> main)) est le message du commit. Dans ce cas, il s'agit de Task4. Ce message donne un résumé du changement effectué dans ce commit, qui, ici, semble être lié à la tâche 4.

### Task 6
En revenant à ce commit avec une commande comme git checkout 5da930b (le hash correspondant à l'"Initial commit"), le dossier de projet a été "restauré" à l'état exact dans lequel il était au moment de ce commit. Cela signifie que tous les fichiers et dossiers ajoutés après ce commit (comme les modifications de Task1, Task2, etc.) disparaissent temporairement de votre espace de travail.

## Gitgraph

### Task 7
1. develop - Une branche nommée develop.
2. c93fcc - Un commit où la branche feature-auth est fusionnée (merge) dans develop avec le message "added user authentication".
3. feature-auth - Une branche nommée feature-auth.
4. Auteur et Email - Détail d'un commit, indiquant l'auteur "CodeQueen Carol" et son adresse email carol.codequeen@hevs.ch.
5. main et v1.0.0 - Le tag v1.0.0 associé à la branche main, pointant vers le commit qui fusionne develop dans main.
6. Ligne de temps des commits - Représentation de l'historique des commits dans la branche develop.
7. Pointeur de branche main - Indique la position actuelle de la branche main.
8. Commit b205e38 - Un commit avec le message "prepare for release".
9. Commit e209ecc - Un commit avec le message "added frontend".
10. Commit e83fbdc - Le commit initial du dépôt.

Pour le second point de l'exercice :

Pour pousser votre dépôt local vers le dépôt distant GitHub, utilisez la commande :
git push origin main

