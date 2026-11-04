# Analyse des logements Airbnb à Toronto

Projet de machine learning réalisé dans le cadre de notre formation à l’EFREI.

## Auteurs

- Gwendal Lavolee
- Karl Anthony Garozzo

## Présentation du projet

Ce projet étudie les caractéristiques des logements Airbnb à Toronto
à partir d’un dataset disponible sur Kaggle.

Nous cherchons à comprendre les facteurs associés aux prix des logements,
à identifier des groupes de locations similaires et à prédire le type
de location à l’aide de méthodes de machine learning.

## Problématique

Dans quelle mesure les caractéristiques des logements Airbnb à Toronto
permettent-elles d’expliquer leur prix et de distinguer différents
profils de locations ?

## Données

- Source : [Toronto Airbnb Dataset — Kaggle](https://www.kaggle.com/datasets/robinkongninglo/toronto-airbnb-dataset)
- Fichier : `listings_sep_09_2020.csv`
- Période de collecte : septembre 2020
- Nombre d’annonces : 19 343
- Nombre de variables : 74

Chaque ligne représente une annonce Airbnb. Les variables décrivent
notamment le prix, la localisation, le type de location, la capacité
d’accueil et les évaluations.

Les données décrivent une période marquée par la pandémie de COVID-19.
Les résultats ne représenteront donc pas nécessairement le marché actuel.

## Analyses prévues

1. Exploration et description des données.
2. Nettoyage et traitement des valeurs manquantes et aberrantes.
3. Clustering avec K-means et classification ascendante hiérarchique.
4. Régressions linéaires simple et multiple pour expliquer le prix.
5. Classification avec KNN pour prédire le type de location.
6. Évaluation des modèles et interprétation des résultats.

## Outils envisagés

- Python et Jupyter Notebook / Google Colab
- pandas et NumPy
- Matplotlib et Seaborn
- scikit-learn et statsmodels
- SciPy

## Livrables

- Un notebook contenant le code, les graphiques et les interprétations.
- Une présentation PowerPoint de la démarche et des résultats.

## État du projet

Dataset sélectionné et première inspection effectuée.
Prochaine étape : exploration détaillée et préparation des données.
