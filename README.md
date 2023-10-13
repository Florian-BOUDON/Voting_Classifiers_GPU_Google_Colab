# Voting Classifiers with GPU on Google Colab

## Présentation du projet

Ce projet a pour objectif de démontrer comment utiliser les capacités de calcul GPU offertes par Google Colab (compte payant) pour construire un Voting Classifier.      
Ce Voting Classifier est constitué de modèles linéaires et non linéaires, et ses hyperparamètres sont sélectionnés grâce à une recherche de grille (GridSearch).    
Les principales métriques évaluées sont la matrice de confusion, la courbe ROC, l'AUC (Area Under the Curve), la précision (accuracy), et la courbe de seuil de rappel-précision.    

## Description du dataset

Le jeu de données utilisé pour ce projet est caractérisé par les éléments suivants :

- Le jeu de données est nettoyé : toutes les données manquantes ou aberrantes ont été traitées.
- Le jeu de données est déséquilibré avec une répartition de 90% pour une classe et 10% pour l'autre.
- taille : 105Mo
- Target codée en {0,1} en proportion 90-10

## Prérequis
Avant de commencer, assurez-vous d'avoir les librairies Python suivantes installées sur votre environnement :

Python 3
scikit-learn
matplotlib
cuml
XGBoost
time
numpy


## Plan
Le projet suit le plan suivant :

1. Importation des librairies nécessaires à l'utilisation des GPU
2. Sélection des variables par arbre de décisions
3. Création et comparaison de modèles linéaires et non-linéaires
4. Création et comparaison du voting classifier

## Structure des fichiers

├── Voting_Classifier.ipynb     
├── df.csv     
├── Présentation.ppt     
└── README.md


## Conclusion
Ce projet se concentre sur la méthodologie et l'utilisation des méthodes plutôt que sur les résultats eux-mêmes.     
L'objectif est de montrer comment utiliser efficacement les capacités de calcul GPU de Google Colab pour construire un Voting Classifier performant.    
Nous encourageons les utilisateurs à explorer le code et à ajuster les paramètres pour leurs propres besoins.
