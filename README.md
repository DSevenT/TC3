# TC3
Projet d'app web
1. Cahier des charges

Le module raytracer fourni pour les projets ne comporte que très peu d'objets composés (Cube, Cylindre, Cône tronqué). L'objectif de ce projet est de : 
créer de nouveaux objets composés comme des polyèdres (pyramide, maison, ...), ou des arbres (sphère + cylindre, cône + cylindre), 
concevoir une interface permettant de créer des scènes comportant ce type d'objets. 

L'interface permettra : 
d'ajouter ou de retirer des objets de la scène, 
de définir la position, et l'orientation des objets, 
la taille de l'image générée. 
Les images seront générées à la volée ou sur demande. Elles devront pouvoir être consultées sans être regénérées si elles existent déjà pour un choix de paramètres donné (notion de cache serveur).
Pour des raisons de simplicité, les couleurs des objets pourront être fixées (i.e. non modifiables). De même, il ne sera pas forcément nécessaire de pouvoir modifier la position de la caméra, et les sources d'éclairage pourront être prédéfinies.
