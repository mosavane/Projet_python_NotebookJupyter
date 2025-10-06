# Projet Data Science : Prédiction du Départ d’un Employé (Churn RH)

## Contexte

Dans un contexte de gestion des clients, la rétention des meilleurs profils est un enjeu majeur. 
Comprendre les raisons qui poussent un client à quitter le navire permet de mettre en place des actions préventives.

Ce projet a pour objectif de construire un modèle de prédiction permettant d’identifier si un employé est susceptible de quitter le groupe, à partir de données historiques.

---

## 🎯 Objectifs

- Analyser les données pour mieux comprendre les comportements de départ.
- Nettoyer et préparer les données pour l'entraînement de modèles prédictifs.
- Tester plusieurs algorithmes de machine learning pour prédire le départ d’un clients.
- Évaluer et comparer les performances des modèles.
- Déployer une application web interactive pour aider la direction à anticiper les risques de churn.

---

## Étapes du Projet

### 1. Exploration des données
- Gestion des valeurs manquantes
- Analyse univariée (variables catégorielles et numériques)
- Analyse bi-variée (corrélations, dépendances)
- Création de nouvelles variables
- Tests statistiques (T-test)

### 2. Modélisation
- Modèles testés :
  - Logistic Regression
  - Random Forest
  - K-Nearest Neighbors
  - Gaussian Naive Bayes
  - Support Vector Classifier
  - XGBoost
- Évaluation des performances : accuracy, confusion matrix, F1-score
- Sélection du meilleur modèle
- Analyse des variables importantes (Feature Importance)

### 3. Visualisation
- Boxplots
- Graphiques comparatifs
- Matrice de confusion

### 4. Application Web
- Dashboard interactif avec Streamlit ou Dash
- Visualisation des données
- Prédictions en temps réel
- Explication des résultats

---

## Technologies utilisées

- Python
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Streamlit / Dash (pour le dashboard web)
- Power BI (visualisation interactive)
---

## ✅ Résultat

Un outil interactif permettant aux responsables d’anticiper le départ potentiel d’un client, basé sur des modèles de machine learning entraînés sur des données historiques.

---

## 📁 Structure du dépôt
