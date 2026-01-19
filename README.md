# Fluid Response Analysis

## Projet d’analyse de la réponse au remplissage vasculaire en réanimation

Ce projet vise à analyser la réponse hémodynamique de patients de réanimation à une intervention de remplissage vasculaire, à partir de signaux physiologiques enregistrés au cours du temps.

L’objectif est d’extraire des métriques statistiques et fréquentielles à partir des signaux, puis d’évaluer leur capacité à discriminer les patients répondeurs des non-répondeurs.

---

## Structure du projet

### 📁 data
Ce dossier contient les données utilisées pour l’analyse.

- Les données brutes d’origine sont présentes.
- Certaines données ont été **prétraitées et légèrement modifiées** afin d’adopter une **structure homogène et universelle**, compatible avec l’ensemble du pipeline de traitement implémenté dans le code.

---

### 📁 notebooks
Ce dossier regroupe l’ensemble des notebooks Python utilisés pour l’analyse.

- **functions.ipynb**  
  Contient l’ensemble des fonctions principales utilisées dans le projet (prétraitement, extraction de métriques, segmentation, etc.).

- **analysebivarieretpvalues.ipynb**  
  Analyse bivariée des métriques et calcul des p-values à l’aide du test de Mann–Whitney U.

- **analysefrequentielle.ipynb**  
  Début de réflexion et d’implémentation d’une analyse fréquentielle des signaux physiologiques.

- **boxplot.ipynb**  
  Visualisation des métriques sous forme de boxplots pour la comparaison entre répondeurs et non-répondeurs.

- **displaysignalswithsptialtimes.ipynb**  
  Affichage des signaux temporels avec des marqueurs indiquant les différentes étapes du protocole expérimental.

- **k_mean.ipynb**  
  Application de l’algorithme de clustering K-means pour explorer la séparation des patients à partir des métriques extraites.

- **regle de decision.ipynb**  
  Tests de normalité des différentes métriques et réflexion autour de règles de décision statistiques.

---

## Remarque
Ce projet s’inscrit dans une démarche exploratoire combinant analyse statistique, visualisation et méthodes de machine learning non supervisées.
