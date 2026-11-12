# Jeu-FIND-MY-WORD

Projet réalisé en binôme en première année de BUT Informatique. L'idée était de recréer en Java une version dans le terminal du jeu Wordle, où il faut deviner un mot de cinq lettres en six essais maximum.

On a d'abord préparé les diagrammes de classes UML pour bien organiser le code avant de se lancer dans le développement. Le jeu fonctionne grâce à plusieurs classes principales : `WordRepository` qui permet de charger le mot secret (soit au hasard depuis un fichier JSON, soit un mot fixe pour nos tests), `Word` qui vérifie que les mots proposés sont valides, et `Game` qui gère toute la partie, vérifie les lettres (`OK`, `PRESENT`, `ABSENT`) et affiche la grille au fur et à mesure.
