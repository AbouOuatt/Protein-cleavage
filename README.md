# Prédiction des Sites de Clivage des Peptides Signal

## But du projet

Ce projet vise à prédire les sites de clivage dans les séquences protéiques en utilisant des modèles d'apprentissage supervisé, notamment les Machines à Vecteurs de Support (SVM). L'objectif est de contribuer à la recherche biologique et biomédicale.

## Technologies utilisées

- **Python** : Langage principal utilisé.
- **Bibliothèques principales :**
  - Scikit-learn : Modélisation et apprentissage supervisé.
  - NumPy, Pandas : Manipulation des données.
  - Matplotlib, Seaborn : Visualisation (optionnel).

## Approche méthodologique

1. **Encodage des données** : Représentation des acides aminés sous forme de vecteurs binaires.
2. **Labelisation** : Identification des séquences contenant un site de clivage (1) ou non (0).
3. **Implémentation SVM** : Utilisation de différents noyaux pour choisir le plus performant (RBF).
4. **Validation** : Évaluation des performances à l'aide de métriques (accuracy, recall, etc.).

## Résultats

- Meilleures performances obtenues avec le noyau RBF : précision moyenne de 77,4 %.
- Précision notable pour les organismes Gram+ procaryotes (90,7 %), mais performances plus faibles pour les eucaryotes et Gram- procaryotes.


