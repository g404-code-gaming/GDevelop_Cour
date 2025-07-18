# Point de vie

Dans ce module, on souhaite créer un système de points de vie à nos ennemis, afin qu'ils puissent être attaqués par des projectiles et disparaître s'ils n'ont plus de PV.

![image 1]() 

Pour commencer, nous allons créer une variable PV pour nos ennemis : 

Dans la scène, cliquez sur l'objet de votre ennemi : 

![image 2]() 

Allez dans Variables.

![image 3]() 

Ajoutez une variable.

![image 4]() 

Nommez cette variable **PV**, elle est de type **Nombre**, et sa valeur sera de **5**. 

![image 5]() 

Une fois que c'est fait, nous allons programmer l'impact des projectiles : allez dans les évènements et ajoutez un nouvel évènement.

![image 6]() 

Pour cet évènement, ajoutez une Condition.

![image 7]() 

La condition est la suivante : lorsque l'ennemi est en collision avec un projectile. 

![image 8]() 

Ajoutez ensuite les actions. Il y en a plusieurs :  
  - On modifie la variable PV de l'ennemi : on y soustrait 1.  
  - On supprime le projectile.

![image 9]()  
![image 10]() 

Désormais, notre ennemi perd des PV en étant touché par des projectiles. Néanmoins, cela ne signifie pas qu'il meurt : il s'agit d'un tout nouvel évènement ! 

Ajoutez un nouvel évènement pour coder la mort de l'ennemi. 

![image 11]() 

Ajoutez dans cet évènement une nouvelle condition. 

![image 12]() 

La condition vérifie si la variable PV de l'ennemi atteint 0. 

![image 13]() 

Ajoutez ensuite une action pour faire disparaître le personnage. 

![image 14]() 

En informatique, pour faire disparaître un objet, on le supprime. 

![image 15]() 

Et voilà, nous avons désormais tous les évènements pour que nos ennemis se fassent détruire par des projectiles.

![image 16]() 
