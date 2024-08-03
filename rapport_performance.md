# Rapport sur les Performances des Modèles de Détection de Fraude

## Introduction

Ce rapport présente une analyse des performances de divers modèles de détection de fraude, incluant des modèles de réseaux de neurones convolutifs (CNN) et des modèles d'apprentissage automatique traditionnels. Les métriques évaluées incluent l'accuracy, la précision, le recall et le F1-Score.

## Performances des Modèles CNN

### 1. ResNet50
- **Accuracy**: 0.666667
- **Precision**: 0.666667
- **Recall**: 1.0
- **F1-Score**: 0.8

### 2. InceptionV3
- **Accuracy**: 0.666667
- **Precision**: 0.666667
- **Recall**: 1.0
- **F1-Score**: 0.8

### 3. VGG16
- **Accuracy**: 0.666667
- **Precision**: 0.666667
- **Recall**: 1.0
- **F1-Score**: 0.8

### 4. MobileNetV2
- **Accuracy**: 0.666667
- **Precision**: 0.666667
- **Recall**: 1.0
- **F1-Score**: 0.8

### 5. EfficientNetB0
- **Accuracy**: 0.666667
- **Precision**: 0.666667
- **Recall**: 1.0
- **F1-Score**: 0.8

### Observations

Tous les modèles CNN présentent des performances identiques avec une accuracy de 0.666667, une précision de 0.666667, un recall de 1.0 et un F1-Score de 0.8. Cette uniformité des résultats suggère que les modèles pourraient être limités par des facteurs communs, tels que la qualité des données d'entraînement ou la complexité des caractéristiques de fraude.

## Performances des Modèles d'Apprentissage Automatique

### 1. SVM
- **Accuracy**: 0.962791
- **Precision**: 0.989880
- **Recall**: 0.935142
- **F1-Score**: 0.961733

### 2. KNN
- **Accuracy**: 1.000000
- **Precision**: 1.000000
- **Recall**: 1.000000
- **F1-Score**: 1.000000

### 3. RandomForest
- **Accuracy**: 0.954953
- **Precision**: 0.923373
- **Recall**: 0.992248
- **F1-Score**: 0.956572

### 4. LightGBM
- **Accuracy**: 0.977562
- **Precision**: 0.992013
- **Recall**: 0.962877
- **F1-Score**: 0.977228

### 5. CatBoost
- **Accuracy**: 0.900689
- **Precision**: 0.857296
- **Recall**: 0.961413
- **F1-Score**: 0.906374

### 6. NaiveBayes
- **Accuracy**: 0.888415
- **Precision**: 0.975635
- **Recall**: 0.796727
- **F1-Score**: 0.877151

### 7. DecisionTree
- **Accuracy**: 0.905383
- **Precision**: 0.881495
- **Recall**: 0.936693
- **F1-Score**: 0.908256

### 8. AdaBoost
- **Accuracy**: 0.764212
- **Precision**: 0.692501
- **Recall**: 0.950474
- **F1-Score**: 0.801234

### 9. LogisticRegression
- **Accuracy**: 0.966236
- **Precision**: 0.997427
- **Recall**: 0.934884
- **F1-Score**: 0.965143

### 10. XGBoost
- **Accuracy**: 0.934841
- **Precision**: 0.907170
- **Recall**: 0.968820
- **F1-Score**: 0.936982

### Observations

Les modèles d'apprentissage automatique traditionnels montrent des performances nettement supérieures à celles des modèles CNN. Le modèle KNN affiche des performances parfaites, ce qui est inhabituel et pourrait indiquer un surapprentissage ou une évaluation sur des données de test similaires aux données d'entraînement. Les modèles SVM, LightGBM, et LogisticRegression montrent également des performances très élevées.

## Recommandations pour l'Amélioration des Performances

### Pour les Modèles CNN
1. **Augmentation des Données**: Utiliser des techniques d'augmentation des données pour enrichir le jeu de données d'entraînement.
2. **Hyperparamètres**: Ajuster les hyperparamètres des modèles pour mieux capturer les caractéristiques de fraude.
3. **Ensemble de Modèles**: Combiner les prédictions de plusieurs modèles CNN pour améliorer la performance globale.

### Pour les Modèles d'Apprentissage Automatique
1. **Validation Croisée**: Utiliser la validation croisée pour éviter le surapprentissage et obtenir une estimation plus fiable des performances.
2. **Sélection de Caractéristiques**: Appliquer des techniques de sélection de caractéristiques pour améliorer la qualité des données d'entrée.
3. **Ensemble de Modèles**: Combiner les prédictions de plusieurs modèles d'apprentissage automatique pour améliorer la performance globale.

## Conclusion

Les modèles d'apprentissage automatique traditionnels, en particulier KNN, SVM, LightGBM, et LogisticRegression, montrent des performances supérieures à celles des modèles CNN pour la détection de fraude. Les modèles CNN pourraient bénéficier d'une augmentation des données et d'un ajustement des hyperparamètres. Pour les modèles d'apprentissage automatique, une validation croisée et une sélection de caractéristiques pourraient améliorer encore les performances.