# Détection de fraude par carte de crédit avec Deep Learning

## Description
Ce projet a pour objectif de **détecter les transactions frauduleuses sur un dataset de cartes de crédit** en utilisant des techniques de **Deep Learning**. Le modèle apprend à partir de données historiques pour prédire si une transaction est frauduleuse ou non. Ce projet met l'accent sur l'utilisation de métriques telles que la **précision**, le **rappel**, le **F1-score** et la **courbe ROC** pour évaluer les performances du modèle, tout en traitant le problème de **déséquilibre des classes** avec la technique **SMOTE**.

## Dataset
Le dataset utilisé dans ce projet provient de **Kaggle**.

## Objectifs
- **Prédiction des transactions frauduleuses** sur un dataset de cartes de crédit.
- Utilisation des techniques de **Deep Learning** pour apprendre les patterns de fraude.
- Evaluation du modèle avec des **métriques pertinentes** (AUC, précision, rappel, etc.).
- Gestion du **déséquilibre des classes** par **SMOTE** (Synthetic Minority Over-sampling Technique).
- Visualisation des résultats à travers des graphiques comme la **matrice de confusion** et la **courbe ROC**.

## Prérequis
Avant de commencer, assurez-vous d'avoir les logiciels et bibliothèques suivants installés :

- **Python** (version 3.x)
- **TensorFlow** / **Keras** (pour l'implémentation du modèle de deep learning)
- **Scikit-learn** (pour le calcul des métriques et la gestion des données)
- **Imbalanced-learn** (pour SMOTE)
- **Matplotlib** et **Seaborn** (pour la visualisation)

Vous pouvez installer les dépendances nécessaires via `pip` :

```bash
pip install tensorflow scikit-learn imbalanced-learn matplotlib seaborn

