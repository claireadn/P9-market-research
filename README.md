Note: Le notebook a été mis à jour avec un code plus cohérent et moins long / The notebook has been updated with more cohesive and shorter code.

# Produisez une étude de marché avec R ou Python

La poule qui chante, une entreprise française d’agroalimentaire qui souhaite se développer à l'international. Aucun pays particulier ni aucun continent n'est pour le moment choisi. Tous les pays sont envisageables !

**(Find the English translation below.)**

## Mission

Objectif : Proposer une première analyse des groupements de pays à cibler pour le lancement à l’international, autrement dit l’exportation de poulets.

* Si utilisation des critères de l’analyse PESTEL -> Récupération des données en open data sur le site de la FAO.
* Tester la classification ascendante hiérarchique avec **un dendogramme.**
* Utiliser la méthode des **k-means** pour analyser l’analyse et comparer les résultats des deux méthodes de clustering.
* Analyser les **centroïdes** des classes.
* Réaliser une **ACP** afin de visualiser les résultats de l’analyse, comprendre les groupes, les liens entre les variables, les liens entre les individus.

Autonomie sur le choix des données à analyser.

**PESTEL :**
* Politique → Stabilité politique par pays (2017)
* Economique → Indice de la consommation par pays (2017) + Évolution de l’indice de la consommation (2000 à 2018) + Taux de change par pays (2017) + Évolution du taux de change (2000 à 2018)
* Social → Population par pays (2017) + Évolution de la population (2000 à 2018) + Disponibilité alimentaire en calories par habitant (2017) + Importation de la volaille par pays (2017) + Production de la volaille par pays (2017)
* Ecologique → Distance par rapport à la France + Émissions crées par la nourriture par habitant (2017)

## Compétences évaluées

* Effectuer un clustering simple
* Explorer des données pour synthétiser des variables

## Livrable

* Notebook Jupyter contenant la préparation, le nettoyage et l’analyse exploratoire des données.
* Notebook Jupyter contenant le/les clusterings effectués, et les différentes visualisations associées.
* Une présentation du travail réalisé (Powerpoint ou équivalent, maximum 20 slides) :
    - Contexte du projet de data analyse,
    - Démarche (sans entrer dans les détails mathématiques, mais en vulgarisant les sujets abordés),
    - Résultats et recommandations.

.


# Produce a market study with R or Python

La poule qui chante, a French food company, is looking to expand internationally. No particular country or continent has been chosen yet. Any country is possible!

## Mission

Objective: Propose an initial analysis of country groupings to target for international launch, i.e. chicken exports.

* If using PESTEL analysis criteria -> Retrieve open data from the FAO website.
* Test hierarchical ascending classification with **a dendogram**.
* Use the **k-means** method to analyze the analysis and compare the results of the two clustering methods.
* Analyze class **centroids**.
* Perform a **ACP** to visualize the results of the analysis, understand the groups, the links between variables and the links between individuals.

  Autonomy over the choice of data to be analyzed.

**PESTEL:**
* Political → Political stability by country (2017)
* Economic → CPI by country (2017) + CPI average evolution (2000 to 2018) + Exchange rate by country (2017) + Exchange rate average evolution (2000 to 2018)
* Social → Population by country (2017) + Population Growth (2000 to 2018) + Food availability in calories per capita (2017) + Poultry imports by country (2017) + Poultry production by country (2017)
* Ecological → Distance from France + Emissions created by food per capita (2017)

## Skills assessed

* Perform simple clustering
* Explore data to synthesize variables
  
## Deliverable

* Jupyter Notebook containing data preparation, cleaning and exploratory analysis.
* Jupyter Notebook containing the clustering(s) performed, and the various associated visualizations.
* A presentation of the work carried out (Powerpoint or equivalent, maximum 20 slides):
    - Context of the data analysis project,
    - Approach (without going into mathematical detail, but popularizing the topics covered),
    - Results and recommendations.
