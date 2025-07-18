# Attaque

Dans ce module, nous allons montrer comment attaquer avec le personnage en utilisant le bouton de la souris. 

![image 1]()

L'objectif est de permettre au personnage de tirer des projectiles lorsque le joueur appuie sur le bouton gauche de la souris. 

Allez dans les évènements de la scène.

Dans l'évènement préfait possédant pour condition '*au lancement de la scène*', ajoutez une action. 

![image 2]()

On va initialiser un chronomètre d'attaque pour le personnage. Ce chronomètre va permettre de savoir s'il peut attaquer ou non (sinon, il va attaquer à l'infini, et ce n'est pas ce qu'on veut). 

![image 3]()

Maintenant, créez un nouvel évènement. 

![image 4]()

Dans cet évènement, ajoutez une Condition.

![image 5]()

On souhaite que l'évènement se déclenche lorsque le bouton gauche de la souris est pressé : recherchez la condition appropriée dans la barre de recherche et choisissez le bon bouton.

![image 6]()

Une fois la 1ère condition faite, il faut vérifier que le personnage peut attaquer en ajoutant une nouvelle condition.  
Celle-ci vérifie si la valeur du chronomètre est valide (ici, on peut tirer toutes les 1 secondes).

![image 7]()

Maintenant que les conditions d'attaque sont remplies, nous allons ajouter l'action. 

![image 8]()

L'action consiste à faire apparaître un projectile, puis à lui appliquer une force pour qu'il bouge vers l'avant. 

Commençons par l'action de création du projectile :  
Pour qu'il apparaisse sur le personnage, on utilise sa position X et Y comme référence. 

![image 9]()

Ensuite, ajoutons l'action qui applique une force au projectile :  
On choisit de déplacer le projectile uniquement sur l'axe X, afin qu'il avance vers la droite.

![image 10]()

Il faut rajouter une dernière action : celle qui va réinitialiser le chronomètre. Ainsi, le personnage pourra attaquer à nouveau dans la prochaine seconde.

![image 11]()

Et voilà, désormais, notre personnage peut attaquer en lançant des projectiles. 

![image 12]()
