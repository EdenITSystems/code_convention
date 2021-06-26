### code_convention
Les conventions de travail de l'entreprise Eden It Systems

# Introduction

La définition ou l’utilisation de convention au sein d’une équipe, d’une entreprise ou d’une communauté favorise la pérennité des projets qui y adhèrent. Les bénéfices sont multiples à savoir : l’uniformité des travaux effectués, une analyse et une lecture de l’historique du projet plus aisé, une réduction de temps d’apprentissage du contexte projet pour un acteur connaissant ces conventions et une optimisation et la création de nouveau projet basés sur des règles existantes.

# convention de travail sur Git/GitHub

# 1- convention des commits

Le bon nommage des messages de commits est un signe de la qualité de la gestion du projet et du bon découpage des tâches.
Le but est de definir un schema logique d'écriture de ces messages, car git n'impose aucune contrainte.

Voici un squelette de message de commit : 

    - [type] : <message>

Parmi les différents "types" de commit nous pouvons avoir : 

    -feat : ajout de fonctionnalité.
    -refactor : changement du code qui ne change rien au    fonctionnement.
    -fix : correction de bugs.
    -style : changement du style sans changement de la logique.
    -build : Système de build (exemple : gulp, webpack, npm).
    -docs : Documentation.
    -perf : amélioration des performances
    - test : modification des tests (systeme de teste unitaire ou ajout de nouveau teste).
    -update : mise à jour
    -change-bundle : 
    -fix-archi : 
    - ...

Un message de commit ou encore description explique les motivations derrière le changement sans pour autant énumerer tout les changements éffectué

Exemple de nommage de commit : 

    - [docs] : restructuration.


# 2- Convention pour les pulls requests

Etablir une convention pour une pull request est necessaire du fait qu'elle permet de savoir de facons sommaire qu'elles sont les modifications qui ont été apporté.

Voici le squelette d'une pull request : 

    |desc : 
        -<modif 1>
        -<modif 2>
        -<modif 3>
        -<modif n>
    <Niveau de difficulté estimé>****

Exemple :

    |desc : modification du fichier readme
        -REAME.md
        -home.html
        -etc ....
    **