# Point de vie

Dans ce module, on souhaite créer un système de points de vie à nos ennemis, afin qu'ils puissent être attaqués par des projectiles et disparaître s'ils n'ont plus de PV.

![image 1](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_1.JPG) 

Pour commencer, nous allons créer une variable PV pour nos ennemis : 

Dans la scène, cliquez sur l'objet de votre ennemi : 

![image 2](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_2.JPG) 

Allez dans Variables.

![image 3](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_3.JPG) 

Ajoutez une variable.

![image 4](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_4.JPG) 

Nommez cette variable **PV**, elle est de type **Nombre**, et sa valeur sera de **5**. 

![image 5](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_5.JPG) 

Une fois que c'est fait, nous allons programmer l'impact des projectiles : allez dans les évènements et ajoutez un nouvel évènement.

![image 6](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_6.JPG) 

Pour cet évènement, ajoutez une Condition.

![image 7](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_7.JPG) 

La condition est la suivante : lorsque l'ennemi est en collision avec un projectile. 

![image 8](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_8.JPG) 

Ajoutez ensuite les actions. Il y en a plusieurs :  
  - On modifie la variable PV de l'ennemi : on y soustrait 1.  
  - On supprime le projectile.

![image 9](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_9.JPG)  
![image 10](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_10.JPG) 

Désormais, notre ennemi perd des PV en étant touché par des projectiles. Néanmoins, cela ne signifie pas qu'il meurt : il s'agit d'un tout nouvel évènement ! 

Ajoutez un nouvel évènement pour coder la mort de l'ennemi. 

![image 11](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_11.JPG) 

Ajoutez dans cet évènement une nouvelle condition. 

![image 12](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_12.JPG) 

La condition vérifie si la variable PV de l'ennemi atteint 0. 

![image 13](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_13.JPG) 

Ajoutez ensuite une action pour faire disparaître le personnage. 

![image 14](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_14.JPG) 

En informatique, pour faire disparaître un objet, on le supprime. 

![image 15](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_15.JPG) 

Et voilà, nous avons désormais tous les évènements pour que nos ennemis se fassent détruire par des projectiles.

![image 16](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_16.JPG) 
