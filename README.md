Accidents routiers en France
==============================
Résumé
L’objectif de ce projet est d’essayer de prédire la gravité des accidents routiers en France. Les prédictions seront basées sur les données historiques répertoriées sur le site du gouvernement.
Après avoir appliqué différentes méthodes pour nettoyer le jeu de données et extrait les caractéristiques qui nous semblaient être pertinentes pour estimer la gravité des accidents, nous avons créé un modèle de Machine Learning pour essayer de prédire la gravité des accidents routiers en France.

Problématique
Les variables que nous possédons dans notre jeu de données sont des variables catégorielles et nous cherchons à déterminer la gravité des accidents (variable cible) selon un classement qui est le suivant : blesser léger, indemne, hospitalisé et tué.
Nous cherchons donc à classer si les accidents de la route appartiennent à une de ces classes. Ainsi, compte tenu de ces éléments, il semblerait que nous cherchons à traiter une problématique de classification supervisée. 


Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data               <- Should be in your computer but not on Github (only in .gitignore)
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's name, and a short `-` delimited description, e.g.
    │                         `1.0-alban-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, links, and all other explanatory materials.
    │
    ├── reports            <- The reports that you'll make during this project as PDF
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   ├── visualization  <- Scripts to create exploratory and results oriented visualizations
    │   │   └── visualize.py

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
