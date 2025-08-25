# Analyse et Fouille de Graphes sur les Réseaux Sociaux en Temps de Crise

Ce projet se concentre sur l'analyse de données de réseaux sociaux (Twitter) en période de crise pour en tirer des informations cruciales. L'objectif est de transformer des données non structurées en un graphe dynamique, permettant d'identifier les influenceurs, les tendances clés et les structures communautaires.


### Problème et Objectif

En temps de crise ou d'événement majeur, les réseaux sociaux deviennent une source d'information massive et rapide. L'objectif est de développer un pipeline d'analyse pour modéliser le flux d'informations et les interactions entre les utilisateurs afin de :
* Détecter les utilisateurs les plus influents.
* Identifier les thématiques et les sujets émergents.
* Comprendre la dynamique de formation des communautés.



### Technologies et Méthodologies

* **Langage :** Python
* **Librairies clés :**
    * `NetworkX` pour la création, la manipulation et l'analyse de graphes.
    * `Pandas` pour la préparation et l'exploration des données.
    * `Scikit-learn` pour l'application d'algorithmes de Machine Learning, notamment pour le clustering.
    * `Matplotlib` pour la visualisation des résultats et des structures du graphe.
* **Techniques  :**
    * **Fouille de graphes :** Modélisation des données Twitter (utilisateurs, tweets, hashtags) comme un réseau d'entités interconnectées.
    * **Embeddings de Graphes :** Utilisation de l'algorithme `Node2Vec` pour représenter les nœuds du graphe sous forme de vecteurs.
    * **Clustering :** Application de l'algorithme `K-Means` pour identifier des communautés d'utilisateurs partageant des intérêts ou des comportements similaires.


### Réalisations principales

* **Pipeline de données :** Mise en place d'un processus pour charger les données (nœuds et relations) à partir de fichiers JSON et construire le graphe.
* **Analyse de graphe :** Exploration des propriétés du graphe, comme la distribution des degrés, les nœuds les plus centraux, et les chemins d'information.
* **Détection de communautés :** Application de techniques de `clustering` pour regrouper les utilisateurs ayant des comportements similaires.
* **Visualisations :** Création de visualisations interactives pour illustrer la structure du réseau, les relations entre les entités et les communautés identifiées.
* **Système de Recommandation :** Développement d'un système de recommandation de tweets basé sur la similarité et la centralité des nœuds.


