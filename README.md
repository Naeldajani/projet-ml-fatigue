# Prédire la fatigue d'un athlète

Projet de Machine Learning (Centrale Lyon, Bachelor Data Science). Le but est de prédire `fatigue_index` à partir des données physiologiques, biomécaniques et d'entraînement de séances de football et de basket.

- **Données** : `multimodal_sports_injury_dataset_kaggle.csv`, un jeu Kaggle de 15 420 séances
- **Modèle** : forêt aléatoire (`RandomForestRegressor`) dont les paramètres sont réglés par recherche sur grille
- **Résultat** : R² ≈ 0,67 en validation et 0,69 en OOB

| Notebook | Valeurs manquantes remplacées par |
|---|---|
| `notebook projet.ipynb` | la moyenne |
| `notebook projet median.ipynb` | la médiane |
