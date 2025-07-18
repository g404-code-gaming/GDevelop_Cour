# Déplacement

Dans ce module, on vous montre comment déplacer un personnage de gauche à droite en utilisant une touche du clavier.

![image 1]()

On souhaite que notre personnage se déplace lorsque le joueur appuie sur une touche spécifique. 

Il existe des comportements qui permettent d'obtenir ce résultat facilement, mais l'objectif ici est de savoir comment faire à partir des évènements. 

Dans vos évènements, ajoutez un nouvel évènement. 

![image 2]()

Dans ce nouvel évènement, ajoutez une condition. 

![image 3]()

La condition est la suivante : *lorsqu'une touche est pressée*. 

On cherche donc la condition de touche pressée dans la barre de recherche, lorsqu'elle est trouvée, il faut choisisr quelle touche ou souhaite attribué à la condition (ici, on souhaite se déplacer à droite, alors on utilise la touche Right).

![image 4]()

Désormais, il faut ajouter la action. 

![image 5]()

L'action consiste à déplacer le personnage, c'est-à-dire à lui appliquer une force dans une direction spécifique. Puisque l'action s'applique au personnage, on clique sur lui et on cherche une action de force. 

Il faut choisir ensuite la vitesse à laquelle on le déplace (ici 50 sur l'axe x). 

![image 6]()

Et voilà ! nous avont une action qui permet de déplacer le personnage lorsque le joueur appuie sur la touche *Right*. 

![image 7]()

Afin de compléter le module, ajoutez l'évènement qui permet de se déplacer à gauche. C'est le même, mais les actions et conditions sont légèrement différentes. 

![image 8]()
