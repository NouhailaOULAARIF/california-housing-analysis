# California Housing Analysis 

Ce dépôt contient un notebook Jupyter (`.ipynb`) dédié à l'analyse exploratoire et à la visualisation géospatiale du jeu de données immobilier de la Californie (*California Housing dataset*).

## 📋 Description du Projet
L'objectif de ce projet est d'explorer les caractéristiques socio-économiques et géographiques qui influencent les valeurs immobilières en Californie. Le notebook couvre l'importation des données, le profilage des variables (comme le revenu médian, l'âge des logements, la population) et la cartographie des données à l'aide des coordonnées de latitude et longitude.

## 📊 Jeu de Données
Le projet utilise le fichier `california_housing_train.csv` (couramment fourni dans les exemples Google Colab). Il contient **17 000 lignes** et **9 colonnes** :
*   `longitude` / `latitude` : Coordonnées géographiques.
*   `housing_median_age` : Âge médian des logements dans le bloc.
*   `total_rooms` / `total_bedrooms` : Nombre total de pièces et de chambres.
*   `population` / `households` : Population totale et nombre de foyers du bloc.
*   `median_income` : Revenu médian des foyers.
*   `median_house_value` : Valeur médiane des maisons (variable cible).

## 🚀 Fonctionnalités du Notebook
*   **Chargement et Inspection :** Lecture des données avec `pandas` et affichage des structures de tables.
*   **Visualisation Géospatiale :** Génération de graphiques de dispersion (*scatter plots*) avec `matplotlib` représentant la répartition géographique des logements en fonction de leur latitude et longitude.

## 🛠️ Technologies Utilisées
*   **Python 3**
*   **Pandas** : Pour la manipulation et l'analyse des données.
*   **Matplotlib** : Pour la création de visualisations graphiques.
*   **Numpy** : Pour les calculs numériques.
*   **Google Colab** / Jupyter Notebook.

## 📦 Installation et Utilisation

1. clonez le dépôt :
   ```bash
   git clone [https://github.com/NouhailaOULAARIF/california-housing-analysis.git] (https://github.com/NouhailaOULAARIF/california-housing-analysis.git))
