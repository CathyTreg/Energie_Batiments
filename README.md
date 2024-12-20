# Energie_Batiments

Prédire la consommation d’énergie de bâtiments à l'aide de modèles de Machine Learning et expliquer les modèles - Projet réalisé en avril 2024 dans le cadre du parcours de formation DataScientist d'OpenClassrooms.

Contexte : Dans le cadre de son objectif de devenir neutre en émissions de carbone d'ici 2050, la ville de Seattle cherche à optimiser la gestion de la consommation d’énergie et des émissions de CO2 des bâtiments non résidentiels. Des relevés minutieux ont été effectués par la ville en 2016, contenant des informations structurelles, géographiques et énergétiques sur ses bâtiments.

Objectif : Sur la base des données recueillies, prédire les émissions de CO2 et la consommation énergétique des bâtiments, sans recourir à des relevés physiques coûteux.

Tâches :
-	Préparation et exploration des données :
o	Analyser les datasets pour comprendre les relations entre variables et cibles ;
o	Préparer les données pour le modèle : gestion des valeurs manquantes, transformations de variables (normalisation, log), et création de nouvelles caractéristiques ;
-	Modélisation :
o	Tester et simuler différents modèles de prédiction (ElasticNet, SVM, GradientBoosting, RandomForest) en optimisant les hyperparamètres et en réalisant une validation croisée pour choisir le modèle le plus performant ;
-	Interprétation des résultats :
o	Expliquer les prédictions des modèles à l’aide des Shapley values et identifier les caractéristiques les plus influentes sur les résultats ;
o	Évaluer l'impact de l'ENERGY STAR Score sur la prédiction des émissions de CO2, afin de déterminer son utilité dans les modèles.

Résultats : 
-	Prédictions des émissions de CO2 et de la consommation énergétique de chaque nouveau bâtiment de Seattle ;
-	Sur la base de ces informations, la ville pourra mieux planifier ses actions pour atteindre ses objectifs de neutralité carbone en 2050.

Environnement de travail : Jupyter Notebook - Python (via Anaconda), librairies : NumPy – Pandas – Matplotlib – Seaborn – scikit-learn – Folium – SHAP
