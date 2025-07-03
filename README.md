# Prédiction de la gravité des accidents routiers en France entre 2008 et 2023

## Objectif du projet :  
Analyser les données d'accidents de la route en France de 2008 à 2023 pour prédire la gravité des accidents à l’aide de modèles de machine learning supervisés.

## Contexte :  
Ce projet vise à aider les services de secours à mieux allouer leurs ressources en ciblant leurs interventions. L’objectif est de réduire les déplacements inutiles tout en améliorant la rapidité d’intervention sur les accidents graves.

## Organisation des Notebooks :  
- `Accidents_import&cleaning_VF` : couvre l’importation et le prétraitement des données, incluant le nettoyage, la gestion des valeurs manquantes et des doublons, ainsi que la création de nouvelles caractéristiques (feature engineering) et des tests statistiques pour améliorer la qualité des données.

- `Modélisation_Cible_Multiclasse_VF` : dans ce notebook, nous testons nos modèles de machine learning supervisé pour une classification avec les quatre classes originales (indemne, blessé léger, blessé hospitalisé, tué). La technique d’undersampling est appliquée pour équilibrer les classes et évaluer les performances des modèles.

- `Undersampling_Classes_Binaires_VF` : présente le regroupement des quatre classes d’accidents en deux catégories principales (accidents graves vs légers), ramenant ainsi le problème de classification multiclasse à une classification binaire. Nous appliquons la technique d’undersampling pour équilibrer les données déséquilibrées et améliorer les performances des prédictions.

- `Oversampling_Classes_Binaires_VF` : utilise la technique d’oversampling pour équilibrer les données regroupées en deux classes (accidents graves et légers), dans le but de comparer les performances des modèles avec celles des modèles undersampling.

## Résultats :  
Sélection du meilleur modèle et identification des variables clés influençant la gravité des accidents : 
après avoir testé et comparé plusieurs modèles avec différentes techniques d’optimisation, le modèle Random Forest, optimisé via RandomizedSearchCV et utilisant la méthode d’échantillonnage undersampling, s’est révélé le plus performant. Il offre la meilleure combinaison de métriques et répond efficacement à notre problématique, avec un recall de 0,82 sur la classe 1 (accidents graves).

## Impact potentiel :  
Optimisation des interventions d’urgence, meilleure gestion des ressources, et prévention renforcée grâce à l’analyse des facteurs de risque.

## Conclusion :  
Notre modèle le plus performant offre des perspectives concrètes pour optimiser les interventions des services publics et diminuer le nombre de victimes sur les routes. Il permet également d’identifier les principaux facteurs de risque grâce à l’analyse des variables les plus influentes.

Ce projet a été réalisé dans le cadre de la formation Data Scientist chez [DataScientest](https://datascientest.com/).
