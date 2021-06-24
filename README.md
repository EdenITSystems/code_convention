# code_convention
Les conventions de travail de l'entreprise Eden It Systems

# Introduction

La définition ou l’utilisation de convention au sein d’une équipe, d’une entreprise ou d’une communauté favorise la pérennité des projets qui y adhèrent. Les bénéfices sont multiples à savoir : l’uniformité des travaux effectués, une analyse et une lecture de l’historique du projet plus aisé, une réduction de temps d’apprentissage du contexte projet pour un acteur connaissant ces conventions et une optimisation et la création de nouveau projet basés sur des règles existantes.

# convention de travail sur Git/GitHub

# 1- convention des commits

le bon nommage des messages de commits est un signe de la qualité de la gestion du projet et du bon découpage des tâches.
le but est de definir un schema logique d'écriture de ces messages, car git n'impose aucune contrainte.

voici un squelette de message de commit  : 

    - [type] : <message>

Exemple : 
    - [delete-file] : suppression du README

parmi les différents types de commit nous pouvons avoir : 
    -[feat]
    -[review]
    -[refacto]
    -[fix]
    -[update]
    -[change-bundle]
    -[fix-archi]
    -[]
    -[]
    -[]
    - ...

# 2- convention pour les pulls requests

etablir une convention pour une pull request est necessaire du fait qu'elle permet de savoir de facons sommaire qu'elles sont les modifications qui ont été apporté.

voici le squelette d'une pull request : 

    #auteur
    #dev..............................
    |desc : 
        -<modif 1>
        -<modif 2>
        -<modif 3>
        -<modif n>
    <niveau de difficulté estimé>****

Exemple :

    #jaures-kano
    #
    |desc : delete-file
        -REAME.md
        -home.html
        -etc ....
    **

