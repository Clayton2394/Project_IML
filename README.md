## 📝 Description du Projet
Ce projet applique des techniques de **Machine Learning** pour prédire les performances académiques des étudiants. L'objectif principal est d'analyser l'influence de divers facteurs socio-économiques, académiques et personnels (comme les habitudes d'étude, l'assiduité, l'implication des parents, etc.) sur les résultats finaux des examens. 

Il a été réalisé dans le cadre du module "Introduction to Machine Learning" à l'Asia Pacific University (APU).

## 👥 Auteurs
* **Paul Jean Baptiste GOURNAY** (TP096060)
* **Clayton Shema HABYALIMANA** (TP096062)

## 🎯 Objectifs
1. **Analyse Exploratoire des Données (EDA)** : Comprendre la distribution des variables et analyser les corrélations entre les différentes caractéristiques et la variable cible (`Exam_Score`).
2. **Prétraitement des Données** : Gérer les valeurs manquantes, normaliser/standardiser les caractéristiques numériques et comparer différentes techniques d'encodage pour les variables catégorielles (Label Encoding vs One-Hot Encoding).
3. **Modélisation** : Développer et entraîner des modèles d'apprentissage automatique adaptés aux tâches de régression.
4. **Évaluation** : Comparer les performances des modèles (en utilisant le score R², le MAE et le RMSE) pour déterminer l'approche la plus efficace.

## 📊 Dataset
* **Nom** : `StudentPerformanceFactors.csv`
* **Volume** : 6 607 enregistrements d'étudiants.
* **Caractéristiques** : 20 variables distinctes (variables numériques comme `Hours_Studied`, `Attendance`, `Sleep_Hours` et variables catégorielles comme `Parental_Involvement`, `School_Type`, `Peer_Influence`).
* **Variable cible** : `Exam_Score` (Régression).

## 🛠️ Technologies et Bibliothèques Utilisées
Le projet est développé en **Python** via un notebook Jupyter (`StudentPerformancePredictionModel.ipynb`).
* **Manipulation de données** : `pandas`, `numpy`
* **Visualisation** : `matplotlib`, `seaborn`
* **Machine Learning** : `scikit-learn` (LinearRegression, KNeighborsRegressor, StandardScaler, MinMaxScaler, LabelEncoder, OneHotEncoder, etc.)

## 🧠 Modèles de Machine Learning
Deux algorithmes principaux ont été implémentés et comparés :
1. **Régression Linéaire (Linear Regression)** : 
   - Modèle paramétrique incluant une implémentation d'une descente de gradient manuelle.
2. **Régression des K-Plus Proches Voisins (KNN Regression)** :
   - Modèle non paramétrique optimisé pour capturer les relations complexes.

Une comparaison rigoureuse a été effectuée entre l'encodage **Label Encoding** et le **One-Hot Encoding** pour identifier la meilleure technique d'encodage de données catégorielles pour chaque algorithme.

## 🚀 Comment exécuter le projet ?
1. Clonez ce dépôt sur votre machine locale :
2. ```bash
   git clone [https://github.com/Clayton2394/Project_IML.git](https://github.com/Clayton2394/Project_IML.git)
