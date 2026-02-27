# 🩺 Prédiction des Maladies Cardiaques
Ce projet utilise le Machine Learning pour prédire la présence de pathologies cardiaques en se basant sur des données cliniques.

## 🚀 Points Forts du Projet
- **Algorithme** : Random Forest optimisé, stratified CV à 5 folds.
- **Pipeline** : Prétraitement automatisé (Scaling, Imputation).

## 📊 Résultats
Le modèle atteint un score **ROC AUC de 0.95** sur les données de test.

## 🛠️ Installation et Utilisation
1. Créer l'environnement :
   `conda env create -f environment.yml`
2. Activer l'environnement :
   `conda activate [NOM_DE_TON_ENV]`
3. Lancer le notebook :
   `jupyter notebook`

## 📁 Structure
- `data/` : Jeux de données.
- `models/` : Modèle `.pkl` et Scaler sauvegardés.
- `notebook.ipynb` : Analyse complète et entraînement.