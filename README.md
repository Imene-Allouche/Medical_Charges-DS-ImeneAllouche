# 💊 Prédiction des Charges Médicales avec le Machine Learning
---

## 📌 Projet académique

- Ce projet a été réalisé dans le cadre du module **Machine Learning / Régression** 
- Professeur : **Mr. Ben Hamed Bassem** 
- Présenté par : **Imene Allouche** 
- **1 MR ISI** - 2025/2026
---

## 📌 Présentation du projet

Ce projet consiste à construire une chaîne complète de Data Science afin d’analyser et prédire les **charges médicales individuelles**.

Le travail suit les étapes suivantes :

- 🔍 Analyse exploratoire des données 
- 🧹 Nettoyage et prétraitement
- 🤖 Modélisation Machine Learning
- 📊 Évaluation des modèles
- 🎯 Sélection de variables
- 📈 Comparaison des performances

---

## 🎯 Objectif

L’objectif principal est de prédire le montant des **charges médicales (`charges`)** d’un individu en fonction de ses caractéristiques :

- Âge
- Sexe
- IMC (BMI)
- Nombre d’enfants
- Statut fumeur
- Région géographique

---

## 📊 Description du dataset

- Fichier : `medical-charges.csv`
- Nombre d’observations : 1339
- Nombre de variables : 7

| Variable | Description |
|----------|-------------|
| age | Âge de l’assuré |
| sex | Sexe (male / female) |
| bmi | Indice de masse corporelle |
| children | Nombre d’enfants à charge |
| smoker | Statut fumeur (yes / no) |
| region | Région géographique |
| charges | Coût des frais médicaux (variable cible) |

---

## 🧠 Modèles utilisés

- Régression Linéaire
- Ridge Regression (L2)
- Lasso Regression (L1)
- ElasticNet (L1 + L2)

---

## 🔬 Étapes du projet

### 1. Analyse exploratoire des données (EDA)
- Inspection des données
- Analyse univariée (histogrammes, boxplots)
- Analyse bivariée et multivariée
- Matrice de corrélation
- Détection des valeurs aberrantes (IQR)

---

### 2. Prétraitement des données
- Gestion des valeurs manquantes
- Suppression des doublons
- Encodage des variables catégorielles
- Normalisation / standardisation
- Séparation train / test (80% / 20%)

---

### 3. Modélisation
- Entraînement des modèles de régression
- Réalisation des prédictions sur le jeu de test
- Affichage et interprétation des coefficients de chaque modèle
- Validation croisée
- Optimisation des hyperparamètres

---

### 4. Évaluation des modèles
Les métriques utilisées :

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R²
- R² ajusté
- MAPE (optionnel)

---

### 5. Sélection des variables
- Élimination backward (p-value)
- RFE (Recursive Feature Elimination)
- Analyse des coefficients Lasso

---

### 6. Comparaison des modèles
- Ré-entraînement des modèles avec les features sélectionnées
- Calcul des métriques
- Comparaison des performances (All Features vs Selected Features)
- Visualisation des résultats (bar charts)
- Analyse de l’impact de la sélection des features
---

## 📈 Résultats principaux

- Le statut fumeur a un impact très fort sur les charges médicales
- L’âge et le BMI sont des facteurs importants
- La sélection de variables permet de simplifier le modèle sans perte importante de performance

---

## ⚙️ Technologies utilisées

- Python 🐍
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

## 📁 Structure du projet
``` 
Project/
├── Projet1_Machine_Learning_Régression_.ipynb
├── cahier_de_charges.pdf
├── medical-charges.csv
└── README.md 
