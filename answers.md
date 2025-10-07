# Answers of <Bili> <Tacchini> <Biltac>

## Basics
### Task 1
- 1 unstaged change: signifie qu'un fichier a été modifié mais pas encore ajouté à l'index (staging area) pour le prochain commit.

### Task 2
1. Le message de commit "CHG: personal data in
answers.md" indique qu'il y a eu un changement (CHG) dans le fichier answers.md, spécifiquement concernant les données personnelles.

1. Non, un message de commit est obligatoire pour décrire les modifications apportées.

2. Les modifications apportées au fichier answers.md sont maintenant enregistrées dans l'historique des versions du dépôt.

3. Non, il faut pousser (push) les modifications locales vers le dépôt distant pour qu'il soit à jour.

### Task 3
- Nous avons ajouté le fichier README. A part cela le statut de notre dépot est propre.

### Task 4
 - Lorsque je reviens au commit initial, mon répertoire de travail est restauré à l'état où il était lors de ce commit initial. Toutes les modifications apportées après ce commit sont "perdues" dans le répertoire de travail (dans une branche en parallèle), mais elles restent dans l'historique des commits et peuvent être récupérées si nécessaire.
 - Lorsque je reviens au dernier commit, mon répertoire de travail est restauré à l'état où il était lors de ce commit. 

### Task 5
- La différence entre le dépot local et le dépôt distant est que le dépôt local contient les modifications que j'ai effectuées sur mon ordinateur, tandis que le dépôt distant (sur GitHub) ne reflète pas encore ces modifications. Pour synchroniser les deux dépôts, je dois utiliser la commande `git push` pour envoyer mes modifications locales vers le dépôt distant.

- Si je supprimais le dépôt local, je perdrais toutes les modifications non poussées vers le dépôt distant. Cependant, si j'ai déjà poussé mes modifications, elles resteraient disponibles dans le dépôt distant.

### Task 6

- Avec toutes ces manipulations, le dépôt originel, donc celui qui a été forké, n'a pas été modifié. En effet, les modifications ont été faites dans notre propre copie du dépôt (le fork) et non dans le dépôt original. Pour que les modifications soient intégrées dans le dépôt original, il faudrait créer une pull request à partir de notre fork vers le dépôt original.



## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)