# Maestro Git & user stories Course

Bienvenue sur le repository du cours Maestro sur Git !

Nous allons écrire des users stories en suivant le workflow git.

Ce que vous voyez c'est la branche main, la branche qui sera déployée en production. Chaque groupe possède son propre dossier à l'intérieur duquel vous allez avoir 1 fichier découpage et 1 fichier pour une première user-story, pour l'instant encore vierges.

On va découper l'atelier en une première partie sur le découpage de votre épic et une 2nd sur l'écriture de vos users stories.

## 1. Découpage de l'epic

Créer une branche (à partir de la branche main) que vous allez appeler `decoupage-groupe-X`.

Une fois que vous êtes sur cette branche, vous allez dans le dossier de votre groupe, et vous créez une page que vous nommez `decoupage`, et c’est ici que vous écrivez votre découpage.

Ca aura cette tête:
- US1: on est là ça fait ça
- US2: on a cliqué ici il se passe ça
- Etc…

Quand vous vous êtes mis d’accord avec votre groupe sur ce découpage, vous committez, et vous créez un pull request.

Et on fera un premier debrief où je regarderai vos pull requests devant tout le monde, et on verra si on approuve :)


## 2. Ecriture d'une première user story

Vous allez vous rendre sur le fichier US1 de votre groupe, et commencer à remplir ce fichier en suivant le template:

- En tant que... - décrire le contexte, user logué ou non loggué etc...
- Je veux... - l'action que l'on veut faire et ce que l'on veut voir apparaître
- Afin de... - décrire l'objectif de l'utilisateur

et en rajoutant des critères d'acceptance qui serviront à donner des indications sur la manière de tester les users stories. Vous écrirez les critères d'acceptance en suivant le template:

- GIVEN...
- WHEN...
- THEN...

Vous allez également mettre les maquettes correspondantes s'il y en a besoin (vous pouvez glisser/déposer des images directement dans le texte ici-même).

On fait ensuite un premier point tou ensemble sur la première user story que vous avez écrite.

## 3. Ecriture des autres user stories

Vous faites la même chose en créant des nouveaux fichiers pour les autres user stories (max 5) toujours dans les dossiers de vos groupes respectifs.

======================================

Voici les étapes:

Sélectionnez la branche de votre groupe
Chaque personne crée une sous-branche en la nommant avec le format: work-groupe-n-prenom
Cliquez sur le dossier de votre groupe, puis sur le fichier us-1
Vous allez individuellement écrire une première user-story en éditant le fichier en question
Une fois que vous avez écrit votre US, scrollez en bas de la page, indiquez le titre de votre commit de manière explicite , ex: “écriture us1 - update bouton upload”, puis cliquez sur COMMIT CHANGES
Retournez sur la page de votre branche en cliquant sur la navigation
Si vous êtes satisfaits, créer une pull request en clickant sur COMPARE & PULL REQUEST
Clickez sur l’onglet PULL REQUEST, clickez sur une PR de votre groupe, allez dans FILE CHANGES pour lire le travail des gens de votre groupe, mettez des commentaires dans l’onglet CONVERSATION
Lorsque vous recevez des commentaires, prenez-les (ou pas) en compte, modifiez vos US en refaisant les points 3-4-5 de la première partie
Lorsque vous êtes satisfait, mergez la pull request !
Recommencez le process pour les autres US.
