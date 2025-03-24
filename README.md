# La Pluie ne Rentre Pas dans le Métro 🌧🚇

## 📌 Description
Ce projet vise à optimiser la planification des rames du métro à Rennes en tenant compte des variations météorologiques. Grâce à l’apprentissage automatique, nous cherchons à prédire la fréquentation du métro afin d'améliorer la gestion des ressources et la satisfaction des usagers.

## 📂 Contenu du Projet

### Introduction
- Contexte des transports en commun en France
- Problématique métier
- Le cas spécifique de Rennes

### Approche Machine Learning adoptée
- **Transformation des Données**
  - Feature engineering
  - Réduction de dimension
  - Recherche de tendances
  - Constitution des datasets

- **Choix du Modèle**
  - Cross Validation
  - Comparaison des modèles :
    - Random Forest
    - Multiple Regression
    - Gradient Boosting
    - AdaBoost

### Résultats et discussion
- **Modèle Final**
  - Performances du modèle retenu
  - Impact des données météorologiques
  - Analyse des erreurs

### Conclusion

## 🛠 Technologies utilisées
- **Python** : Pandas, NumPy, Scikit-learn, XGBoost
- **Jupyter Notebook** : Analyse des données et entraînement des modèles
- **Matplotlib & Seaborn** : Visualisation des résultats

## 📊 Résultats clés
- **Meilleur modèle** : Gradient Boosting avec un R² de 94%
- **L’ajout des données météorologiques** améliore la précision des prédictions
- **Des erreurs persistent**, rendant difficile l'exploitation opérationnelle

## 📌 Améliorations futures
- Intégrer plus de données historiques pour affiner la précision
- Expérimenter des modèles deep learning
- Travailler sur une meilleure granularité des données de fréquentation
