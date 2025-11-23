# INF4127 TPE_serie2 – Descente de Gradient

## Description du projet


Ce dépôt contient les travaux pratiques réalisés dans le cadre de l'unité **INF4127 : Optimisation II** du programme INF M1 à l'Université de Yaoundé I.

## 🎯 Objectif

Étudier et expérimenter des algorithmes d'optimisation numérique **sans contraintes** sur des fonctions de test multimodales. Ce TPE reprend les méthodes vues dans le support de cours (Chapitre 2, pages 32 à 34).

## 🛠️ Fonctions de Test

Les expérimentations portent sur trois fonctions de deux variables \((x, y)\) :

1. **Rosenbrock **  
   \[
   f(x,y) = (1-x)^2 + 100(y-x^2)^2
   \]
2. **Quadratique**  
   \[
   f(x,y) = x^2 - y^2
   \]
3. **Himmelblau**  
   \[
   f(x,y) = (x^2 + y - 11)^2 + (x + y^2 - 7)^2
   \]

## ⚙️ Travail Réalisé

Pour chaque fonction, le notebook inclut :

- **Visualisation 3D** : Graphique de la surface pour identifier minima, maxima et points selles.
- **Calcul du gradient** : Dérivation symbolique des fonctions.
- **Expérimentation des algorithmes** : Descente de gradient, méthode de Newton, quasi-Newton.
- **Analyse des résultats** :
  - Convergence selon le point de départ.
  - Vitesse de convergence (nombre d'itérations).
  - Capacité à atteindre le minimum global.
  - Influence du learning rate ou de l'algorithme choisi.

## 🧑‍💻 Technologies

- **Langage** : Python 3.x  
- **Bibliothèques** : NumPy, SciPy, Matplotlib  
- **Support** : Jupyter Notebooks (.ipynb)

## 📅 Délais

- **Date limite** : 23 Novembre 2025, 20h00  
- **Rendu** : Via ce dépôt GitHub

## 👥 Auteurs

- Nangmo Feulfack Annick Duplesse (21S2530)    
- Nguefack Tangomo Chris Arthur (0000000)  

**Superviseur :** Pr. Paulin Melatagia

## 📜 Licence

Usage strictement académique et pédagogique.
