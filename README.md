
### Problème et Objectif

Ce projet vise à modéliser et à explorer les interactions sur les réseaux sociaux (Twitter) lors d'événements critiques pour en extraire des informations clés. L'objectif principal est d'analyser les flux d'informations pour identifier les utilisateurs influents, les tendances émergentes et les communautés formées autour de sujets spécifiques.

### Technologies et Méthodologies

* **Langage :** Python
* **Librairies :**
    * `NetworkX` pour la création et l'analyse de graphes
    * `Pandas` pour la manipulation et l'exploration des données
    * `Scikit-learn` pour l'application d'algorithmes de clustering (K-Means)
    * `Matplotlib` pour la visualisation des données
* **Techniques clés :**
    * **Fouille de graphes :** Modélisation des tweets, utilisateurs et hashtags comme des nœuds et des relations.
    * **Embeddings de graphes :** Utilisation de l'algorithme `Node2Vec` pour représenter les nœuds sous forme de vecteurs.
    * **Clustering :** Application de l'algorithme `K-Means` pour identifier les communautés d'utilisateurs.

### 🎯 Réalisations et Résultats

* **Pipeline de données :** Mise en place d'un processus pour charger les données (nœuds et relations) à partir de fichiers JSON et construire le graphe.
* **Analyse de graphe :** Exploration des propriétés du graphe, comme la distribution des degrés, les nœuds les plus centraux, et les chemins d'information.
* **Détection de communautés :** Application de techniques de `clustering` pour regrouper les utilisateurs ayant des comportements similaires.
* **Visualisations :** Création de visualisations interactives pour illustrer la structure du réseau, les relations entre les entités et les communautés identifiées.
* **Système de recommandation :** Développement d'un système pour recommander des tweets.

