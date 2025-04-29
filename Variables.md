# Variables

Une **variable**, c'est un **nom**, associé à une **valeur**, que l'on va pouvoir utiliser et modifier dans le jeu. 

Les variables servent à enregistrer des informations importantes. Elles peuvent notammant servir à : 
   - Compter les points
   - Sauvegarder la vie d'un personnage (PV)
   - Garder un état. *Exemple : est-ce que le personnage possède une clé ?*
   - Contrôler des [évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/%C3%A9v%C3%A8nements.md). *Exemple : Si la valeur de score est au dessus de 100, alors on a gagné.*

Il existe **trois types de variables** dans GDevelop : 

### Variable d'objet 

Les variables d'objets sont associées à un objet spécifique. Elles permettent de représenter des points de vie, de la vitesse, ou pleins d'autres caractéristiques qui sont spécifique à un personnage en particulier.

![évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/variable_1.JPG)

### Variable de scène 

Les variables de scène sont associées à une scène spécifique et non pas à un objet en particulier. Elles permettent de représenter des scores ou de contrôler des évènements.

![évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/variable_2.JPG)

### Variable globales 

Les variables globales sont communes à l'ensemble du jeu, peut importe la scène. Elles permettent de conserver des informations d'une scène à l'autre (comme le score du personnage ou des options).

![évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/variable_3.JPG)

## Créer une variable 

Que ce soit des variables de scène, d'objet ou globales, on peut créer autant de variable que néccessaire. 

![évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/variable_4.JPG)

Lorsqu'on crée une variable, il faut choisir son nom, son type et la valeur qu'elle contient. 

![évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/variable_5.JPG)

Il existes plusieurs types de valeurs pour les variables : 
   -Nombre : un nombre (0,1,2,3,...), utile pour enregistrer des points de vie, du score, des dégâts,....
   -Texte : un texte ("Droit", "gauche", ...), utile pour enregistrer des états différents, comme une direction, une animation, ....
   -Booléan : une valeur qui est soit FAUX, soit VRAI. Utile pour vérifier des états, comme par exemple pour savoir si un personnage porte une arme ou non. 
   -Structure : Une variable de type structure contient d'autre variables, qu'on appelle des enfants. Cela permet de réunir les variables en groupes.
   
## Vérifier / Modifier une variable 

Dans les [évènements](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/%C3%A9v%C3%A8nements.md), on peut accéder aux variables pour vérifier leurs valeurs ou les modifier.

Condition : Valeur d'une variable

Action : Changer la valeur d'une variable

Les paramètres d’une condition ou d’une action incluant une variable varient en fonction du type de cette variable.
