# Projet de Classification et d'Évaluation de Modèles

## Description
Ce dépôt contient trois notebooks distincts, chacun traitant des tâches de classification et d'évaluation de modèles de machine learning.

## 1. Classification d'Images de Voitures
### ImageFraudDetection.ipynb
Ce script est dédié à l'entraînement et à l'évaluation de modèles de Deep Learning pour la classification d'images de voitures en deux catégories : Fraud (simulation d'accidents ou exagération) et Non-Fraud (accidents réels). Il utilise plusieurs architectures de réseaux de neurones pré-entraînés, dont :
- ResNet50
- InceptionV3
- VGG16
- MobileNetV2
- EfficientNetB0

Le script affiche les performances des modèles en termes de précision, rappel, et F1-score et génère des visualisations des prédictions pour un échantillon d'images de test.

## 2. Optimisation et Évaluation de Modèles de Classification
### FraudDetection.ipynb
Ce script est utilisé pour l'optimisation hyperparamétrique de plusieurs modèles de classification en utilisant la bibliothèque Optuna. Les modèles évalués incluent :
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Random Forest
- LightGBM
- CatBoost
- Naïve Bayes
- Decision Tree
- AdaBoost
- Logistic Regression
- XGBoost

Le script effectue une validation croisée pour trouver les meilleurs hyperparamètres pour chaque modèle et évalue leur performance sur l'ensemble de test. Les meilleurs paramètres et scores de performance sont affichés pour chaque modèle.

## 3. Génération de Rapports de Performance
### GeneratePerformanceReport.ipynb
Ce script est conçu pour générer un rapport de performance détaillé des modèles de détection de fraude en utilisant Mistral AI. Le rapport comprend :
- Une analyse comparative des performances des modèles de Deep Learning et des modèles d'apprentissage automatique traditionnels.
- Des recommandations pour améliorer les performances des modèles.
- Un rapport en Markdown qui peut être téléchargé pour une documentation claire et structurée.


