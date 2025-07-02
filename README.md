Accidents routiers en France
==============================
Résumé :
L’objectif de ce projet est d’essayer de prédire la gravité des accidents routiers en France. Les prédictions seront basées sur les données historiques répertoriées sur le site du gouvernement.
Après avoir appliqué différentes méthodes pour nettoyer le jeu de données et extrait les caractéristiques qui nous semblaient être pertinentes pour estimer la gravité des accidents, nous avons créé un modèle de Machine Learning pour essayer de prédire la gravité des accidents routiers en France.

Problématique :
Les variables que nous possédons dans notre jeu de données sont des variables catégorielles et nous cherchons à déterminer la gravité des accidents (variable cible) selon un classement qui est le suivant : blesser léger, indemne, hospitalisé et tué.
Nous cherchons donc à classer si les accidents de la route appartiennent à une de ces classes. Ainsi, compte tenu de ces éléments, il semblerait que nous cherchons à traiter une problématique de classification supervisée. 


Organisation du projet :
------------
La première étape du projet a consisté à explorer les données, sélectionner les variables explicatives les plus pertinentes, puis nettoyer le dataset (valeurs manquantes, doublons, etc.). Un test du chi² a été utilisé pour identifier les variables les plus corrélées à la variable cible. Les données ont ensuite été divisées en jeux d'entraînement et de test, encodées, puis standardisées afin de préparer la modélisation.

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
