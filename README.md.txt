# Prédiction du Prix des Voitures d'Occasion - Projet WardsAuto

Ce projet vise à prédire le prix des voitures d'occasion à partir de leurs caractéristiques techniques et commerciales en utilisant des algorithmes de machine learning.

## 📌 Contexte

Le marché des voitures d’occasion est en pleine expansion. Sur des plateformes comme **WardsAuto**, la diversité des véhicules complexifie l’évaluation juste des prix. Ce projet répond au besoin d’une estimation fiable et automatisée via des modèles prédictifs.

## 🎯 Objectif

Développer et comparer plusieurs modèles de machine learning afin de prédire précisément le prix des voitures d'occasion. L'étude inclut :
- Le nettoyage des données
- Le traitement des valeurs manquantes
- L’ingénierie des variables
- L’optimisation des modèles
- L’interprétation des résultats avec SHAP

## 🗂️ Structure du projet
.
├── data/
│ └── autos.csv # Données brutes depuis Kaggle
├── notebooks/
│ ├── 01_EDA.ipynb # Analyse exploratoire
│ ├── 02_Modeling.ipynb # Entraînement et évaluation des modèles
├── scripts/
│ ├── preprocessing.py # Traitement des données
│ ├── modeling.py # Construction des pipelines ML
├── models/
│ └── best_model.dill # Meilleur modèle sauvegardé
├── output/
│ ├── model_comparison.png # Comparaison visuelle des modèles
│ └── shap_summary.png # Résumé SHAP
├── Presentation_WardsAuto_ML.pptx # Présentation PowerPoint
├── README.md # Ce fichier
