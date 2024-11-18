Que fait la commande git init ?
Git init permet d’initialiser son répertoire en tant que repo git

Quelle est la différence entre git add et git commit ?
Git add permet d’ajouter les fichiers que l’on veut rajouter a git
Git commit permet de mettre un nom et va déplacer sur git en local

Expliquez pourquoi il est important de bien rédiger les messages de commit.
C’est important de bien nommer afin de se retrouver facilement

Quelle est la commande pour ajouter ce fichier au suivi ?
Git add -A git commit -m add_main.c

Que représente chaque ligne dans le résultat de git log ?
Ça Représente chaque commit

À quoi sert git diff ?
Permet de voir les différences entre ce qu’il y a en local et sur la branche

Pourquoi est-il utile d'avoir un fichier .gitignore ?
Pour éviter d’ajouter des fichiers indésirables ou inutiles au repo

Quelle est la différence entre un dépôt public et un dépôt privé ?
Repo public = tout le monde peut le voire repo priver = on choisi qui y a accès, dans les 2 cas on choisi qui peut push sur ce repo

Expliquez à quoi sert la commande git remote add origin
Git remote add origin permet d’ajouter le repo local au projet git 


Que signifie l'option -u dans la commande git push ?
Le -u permet de faire correspondre les branche main et de la créer si elle n’éxiste pas sur repo distant

Pourquoi est-il recommandé de créer une branche pour chaque nouvelle
fonctionnalité ?
C’est important de créer des branches pour pouvoir travailler sur des fonctionnalités sans impacter la main

Quelle commande permet de lister toutes les branches existantes ?
Git branch -a

Pourquoi est-il important de bien documenter une Pull Request ?
C’est important de bien documenter pour expliquer ce qui a été fait et expliquer les contraintes qui ont pu nous amener a faire la modif d’une certaine sorte

Dans quel cas est-il préférable d'utiliser GitHub Flow plutôt que Git Flow ?
Github flow va être utiliser pour des projets ou l’on va utiliser seulement la branche main alors que git flow sera utiliser pour des projets on l’on aura besoin de déployer plusieurs branch

Expliquez le rôle des branches hotfix dans Git Flow.
Hotfix est utiliser pour régler des bugs

Quelle est la différence entre git clone et git pull ?
Git clone importe le repo distant en local 
Git pull apporte les modifications apportées au repo distant en local

Quelles sont les étapes à suivre après avoir résolu un conflit ?
Une fois les conflits résolus on va pouvoir push la version finale

Quelle est la différence entre merge et rebase ?
Merge va permettre d’ajoutez les changements d’une branche à une autre
Rebase va permettre d’importer les changements d’une branche sur celle où l’on est

Dans quel cas utiliseriez-vous cherry-pick ?
Cherry-pick va être utilisez pour prendre un commit particulier et l’ajoutez à notre branche pour exemple si on a une branche de production et une de recette on va cherry-pick une feature de la branche recette sur la branche de production

Pourquoi utiliser des submodules plutôt que copier directement le code
dans votre dépôt ?
Les submodules sont utiliser pour importer un depot git externe au notre

Quelle commande permet de mettre à jour les submodules après un pull ?
Il faut utiliser git submodule update