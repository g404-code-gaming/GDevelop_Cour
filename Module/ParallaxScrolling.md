# 🌌 Module – Parallax Scrolling

## 🎯 Objectif

Découvrir le **parallax scrolling**, comprendre comment utiliser les **calques dans GDevelop**, et apprendre à construire un décor composé de plusieurs plans (**background** et **midground**) qui se déplacent à des vitesses différentes pour donner une **impression de profondeur**.

---

## 🧠 Qu’est-ce que le parallax scrolling ?

- Le **parallax scrolling** est une technique visuelle utilisée dans les jeux vidéo en 2D.  
- Principe : quand le joueur se déplace, les **éléments du décor ne bougent pas tous à la même vitesse**.  
- Résultat : une **illusion de profondeur** (comme si la scène était en 3D).  

👉 Exemple simple :  
- Le **fond lointain** (montagnes, ciel) bouge lentement.  
- Le **milieu** (arbres, collines) bouge plus vite.  
- Le **sol** et le **joueur** bougent normalement.

---

## 🧰 Les outils dans GDevelop

Pour créer du parallax scrolling, on utilise :

1. **Les calques**  
   - Par défaut, tous les objets sont placés sur le calque `Base layer`.  
   - On peut créer d’autres calques (`Background`, `Midground`, `UI`...) pour séparer les éléments.  
   - Chaque calque peut avoir une **caméra indépendante**.

2. **Les Tiled Sprites**  
   - Parfaits pour créer des arrière-plans qui se répètent à l’infini.  
   - Exemple : un ciel ou une forêt qui se répète en largeur.

---

## 🪜 Construire son décor

### 1. Ajouter le **background** (arrière-plan lointain)
- Crée un **Tiled Sprite** appelé `FarBackground`.  
- Mets-y ton image de ciel ou montagnes.  
- Place-le sur un **nouveau calque** `Background`.

### 2. Ajouter le **midground** (décor intermédiaire)
- Crée un autre **Tiled Sprite** appelé `MidBackground`.  
- Mets-y une image d’arbres ou de collines.  
- Place-le aussi sur un **nouveau calque** `Midground`.

### 3. Conserver le sol et le joueur
- Laisse-les sur le calque `Base layer`.  
- Ce sera le plan le plus rapide, celui qui suit la caméra normalement.

---

## 💻 Mise en place du parallax avec les événements

### Principe
- On déplace le **décor en fonction de la caméra**, mais à une vitesse différente.  
- Plus le décor est **loin**, plus il bouge lentement.

### Exemple d’événement
- `FarBackground` → avance à **1/8ème** de la vitesse de la caméra  
- `MidBackground` → avance à **1/3** de la vitesse de la caméra  

---

## ✅ Résultat attendu

- Quand le joueur se déplace :  
  - Le **fond lointain** bouge doucement.  
  - Le **milieu** bouge un peu plus vite.  
  - Le **sol et le joueur** bougent normalement.  
- L’ensemble donne une impression de **profondeur et dynamisme**.

---

## 💡 Astuces

- Ajoute plusieurs couches (jusqu’à 4 ou 5) pour un effet plus riche.  
- Tu peux varier les vitesses (ex. `1/10`, `1/5`, `1/2`...) selon la distance de chaque plan.  
- Les calques `UI` ou `HUD` ne doivent **jamais bouger** avec la caméra (pour les boutons, score, barre de vie).  
- Essaie aussi le **parallax vertical** si ton jeu a du scrolling vers le haut/bas.  
