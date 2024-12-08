# Energie_Batiments

Projet réalisé dans le cadre de ma formation de DataScientist avec OpenClassrooms.

Prédire la consommation d’énergie de bâtiments à l'aide de modèles de Machine Learning et expliquer les modèles.

Contexte : 
-	La ville de Seattle a pour objectif de devenir une ville neutre en émissions de carbone en 2050.
-	Pour se faire, elle s’intéresse de près à la consommation et aux émissions des bâtiments non destinés à l’habitation. Malheureusement, effectuer des relevés de ces mesures pour chaque bâtiment est trop couteux.
-	Des relevés minutieux ont été effectués par les agents de la ville en 2016, et nous avons toutes ces données à disposition. Cette base contient un ensemble de bâtiments avec des données structurelles, géographiques et de mesures d’énergie.

Tâches :
-	Tester différents modèles de prédiction permettant de prédire les émissions de CO2 et la consommation totale d’énergie.
-	Evaluer l’intérêt de l’"ENERGY STAR Score" pour les prédictions, donnée actuellement fastidieuse à calculer avec l’approche utilisée.

Actions : 
-	Réaliser une analyse exploratoire des datasets.
-	Réaliser le feature engineering des données : traitement des valeurs manquantes, transformations de variables (normalisation, log, etc.), création de nouvelles caractéristiques
-	Explorer les relations entre les variables et les targets
-	Simuler différents modèles de prédiction : optimiser les hyperparamètres et le choix de l’algorithme de ML (ElasticNet, SVM, GradientBoosting, RandomForest) à l’aide d’une validation croisée.
-	Evaluer rigoureusement les performances des modèles pour choisir celui qui répond au mieux à la problématique.
-	Expliquer les prédictions des 2 modèles en analysant les shapley values des modèles (caractéristiques qui ont le plus d’importance dans les modèles).
-	Déterminer l’influence de l’"ENERGY STAR Score" sur la prédiction d’émissions de CO2.

Résultats : 
-	Prédire (avec une certaine précision) les émissions de CO2 et la consommation totale d’énergie des nouveaux bâtiments de la ville (sans effectuer de relevés) pour contribuer à l’objectif de ville neutre en émissions de carbone en 2050.

Environnement de travail : Jupyter Notebook - Python (via Anaconda), librairies Numpy – Pandas – Matplotlib – Seaborn – Scikit-learn – Folium – Shap 
