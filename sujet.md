## Plate-forme de tests et d'évaluations de commandes Unix

Les étudiants de première année commencent leurs cours/TP sous Unix dès leur arrivée à l'IUT.

Pour certains ce module pose des difficultés que l'on espère lever, au moins en partie, en proposant un programme permettant la multiplication de petits exercices auto évalués.

Dans sa version simplifiée :

1. Une question “Unix” est posée par le programme
2. L'étudiant propose une réponse et la soumet au programme
3. Le programme évalue la réponse et attribue des points

La version complète, qui reste à définir, devra prendre en compte d'autres possibilités comme par exemple :

* La définition d'un test comme un ensemble de questions parmi celles répondant à 1 ou plusieurs critères (questions éventuellement tirées aléatoirement parmi un ensemble)
* La possibilité d'attribuer une note /20 à l'issue du test
* La possibilité d'effectuer le test à partir d'un navigateur Web connecté à un site (comme par exemple le dokuwiki d'opale.u-clermont1.fr)

Le programme sera réalisé essentiellement en shell bash mais sa mise en place nécessitera également :

* la création d'un système Debian dédié permettant l'authentification des utilisateurs et le test des commandes
* Un peu de JavaScript et de PHP pour la version Web.


