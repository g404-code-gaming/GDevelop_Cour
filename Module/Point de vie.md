# ❤️ Module – Points de vie des ennemis

![image 1](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_1.JPG) 

## 🧰 Besoins

- Un **ennemi**
- Un **projectile**

---

## 🪜 Étapes

### 1. Créer une variable "PV" pour l’ennemi

- Clique sur l’objet **ennemi** dans la scène
- Ouvre l’onglet **Variables**
- Clique sur **Ajouter une variable**
- Nom : `PV`
- Type : **Nombre**
- Valeur de départ : `5`

![image 5](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_5.JPG) 

---

### 2. Enlever 1 PV à l’ennemi quand il est touché

- Crée un **événement** :
  - **Condition** : L’ennemi est en **collision avec un projectile**
  - **Actions** :
    - **Soustraire 1** à la variable `PV` de l’ennemi
    - **Supprimer** le projectile

   ![PV_Code.png](Images/PV_Code.png)

---

### 3. Détruire l’ennemi à 0 PV

- Crée un **nouvel événement** :
  - **Condition** : La variable `PV` de l’ennemi est **inférieure ou égale à 0**
  - **Action** : **Supprimer l’ennemi**

![image 16](https://github.com/g404-code-gaming/GDevelop_Cour/blob/main/Images_cours/PV_16.JPG) 

---

## ✅ Résultat attendu

- L’ennemi perd **1 PV à chaque impact**
- L’ennemi **disparaît quand ses PV atteignent 0**
