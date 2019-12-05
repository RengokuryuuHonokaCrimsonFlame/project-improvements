# TWEB Project : Asteroïd Game Improvements


## Membres du groupe

* Rod Julien
* Rohrbasser Yoann
* Stalder Nicodème

## First Improvement description 

Faire une communication en P2P entre les différents brawsers.

1. Avoir un browser qui prend rôle de pseudo server.
2. Gérer le fait qu'il essaie de passer le rôle de pseudo server à 
un autre s'il quitte la partie ou meurt.


## Second Improvement description

Faire une implémentation pour permettre le PvP.

1. Rajouter une barre de vie au joueur.
2. Ajouter des objets permettants de remonter sa vie.
3. Améliorer la collision avec les astéroids (faire perdre de la vie).
4. Gérer la collision avec des rockets (améliorations du score de celui qui
tire et diminution de la vie de celui qui prend).
5. Gérer la collision avec d'autres spaceships (baisser la vie et le score des
deux joueurs).
6. Gérer la collision avec les objets remontant la vie.
7. Gérer l'explosion des spaceships.
8. Gérer la collision des astéroïdes entre eux (si ne ralentit pas trop le jeu); utilisation du'un quadtree pour optimiser la détection des collisions.
9. Gérer l'écran de game over (new game, quit, pay to continue).
