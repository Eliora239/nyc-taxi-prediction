#  NYC Taxi Fare Prediction

Prédiction du tarif d'une course de taxi à New York à partir de données GPS et temporelles.

## Dataset
Kaggle NYC Taxi Fare Prediction — ~55 millions de lignes, échantillon de 500 000 utilisé.

## Stack technique
- **Python** — langage principal
- **Pandas / NumPy** — manipulation et nettoyage des données
- **Scikit-learn** — modélisation (Random Forest, Régression Linéaire)
- **Matplotlib / Seaborn** — visualisation

## Étapes
1. Chargement et exploration (EDA)
2. Nettoyage des données (valeurs aberrantes, coordonnées hors NYC)
3. Feature Engineering (distance géodésique, variables temporelles, heures de pointe)
4. Modélisation et comparaison de modèles
5. Évaluation (RMSE, R²)

## Résultats

| Modèle | RMSE | R² |
|--------|------|----|
| Régression Linéaire | ~4.2 | ~0.71 |
| Random Forest | ~3.1 | ~0.84 |

## Enseignements clés
- La distance est la variable la plus prédictive
- 80% du travail = nettoyage des données
- Le Random Forest réduit le RMSE de 26% vs la régression linéaire
