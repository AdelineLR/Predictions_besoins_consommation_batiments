# Prédiction des besoins en consommation de bâtiments

_Projet réalisé dans le cadre de la formation Data Scientist d'OpenClassrooms (Projet n°4 - Déc. 2023)_

## Compétences acquises
* Créer les variables pertinentes d'un modèle d'apprentissage supervisé ou non-supervisé
* Sélectionner, entraîner et évaluer des modèles d’apprentissage supervisé

## Contexte
Pour atteindre son objectif de ville neutre en émissions de carbone en 2050, la ville de Seattle s’intéresse de près à la consommation et aux émissions des bâtiments non destinés à l’habitation.
Des relevés minutieux ont été effectués par les agents de la ville en 2016. Cependant, ces relevés sont coûteux à obtenir, et à partir de ceux déjà réalisés, l'objectif est de tenter de prédire les émissions de CO2 et la consommation totale d’énergie de bâtiments non destinés à l’habitation pour lesquels elles n’ont pas encore été mesurées.
La prédiction se basera sur les données structurelles des bâtiments (taille et usage des bâtiments, date de construction, situation géographique, ...).
L'intérêt de la variable "ENERGY STAR Score" pour la prédiction des émissions CO2 et de la consommation totale d'énergie sera également à évaluer.
Le projet se décompose en 3 parties :
* Analyse exploratoire
* Prédiction de la consommation totale d'énergie
* Prédiction des émissions de CO2

## Données
* 2016_Building_Energy_Benchmarking.csv : Données concernant les caractéristiques des bâtiments et leur consommation
  
## Livrables
* LeRay_Adeline_1_Analyse_Exploratoire_122023.ipynb : Analyse exploratoire
* LeRay_Adeline_2_1_Notebook_prédiction_SiteEnergyUse_122023.ipynb : Sélection du meilleur modèle
* LeRay_Adeline_2_2_Notebook_prédiction_SiteEnergyUse_122023.ipynb : Optimisation du modèle
* LeRay_Adeline_2_3_Notebook_prédiction_SiteEnergyUse_122023.ipynb : Evaluation de l'influence de l'Energy Star Score
* LeRay_Adeline_3_1_Notebook_prédiction_TotalGHGEmissions_122023.ipynb : Sélection du meilleur modèle
* LeRay_Adeline_3_2_Notebook_prédiction_TotalGHGEmissions_122023.ipynb : Optimisation du modèle
* LeRay_Adeline_3_3_Notebook_prédiction_TotalGHBEmissions_122023.ipynb : Evaluation de l'influence de l'Energy Star Score
* LeRay_Adeline_4_Presentation_122023.pdf : Présentation de la soutenance du projet
