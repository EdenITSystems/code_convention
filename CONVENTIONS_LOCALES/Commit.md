# Les conventions des commits

Le bon nommage des messages de commits est un signe de la qualité de la gestion du projet et du bon découpage des tâches.
Le but est de definir un schema logique d'écriture de ces messages, car git n'impose aucune contrainte.

## la syntaxe d'un commit 

Voici un squelette de message de commit : 

     [type] : <message>

## Types de commits 

Parmi les différents "types" de commit, nous pouvons citer :   

    -feat : ajout de fonctionnalité.
    -refactor : changement du code qui ne change rien au    fonctionnement.
    -fix : correction de bugs.
    -style : changement du style sans changement de la logique.
    -build : Système de build (exemple : gulp, webpack, npm).
    -docs : Documentation.
    -perf : amélioration des performances
    -test : modification des tests (systeme de teste unitaire ou ajout de nouveau teste).
    -update : mise à jour
    -change-bundle : 
    -fix-archi : 
    - ...

NB: Un message de commit ou encore description, explique les motivations derrière les   modifications apportéesà un projet sans pour autant énumerer tous les changements éffectués.  

Exemple de  commit : 

    - [docs] : restructuration.

