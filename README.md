# Prédiction de l'Absentéisme des Employés

Ce projet a pour objectif d’analyser et de prédire l’absentéisme des employés à l’aide d’un modèle de régression logistique. Il vise à identifier les profils à risque élevé et à fournir des outils d’aide à la décision pour les services RH.

## 📁 Structure du projet


absenteisme-prediction/
├── data/ # Données CSV utilisées pour l’analyse
│ ├── Absenteeism_data.csv
│ ├── Absenteeism_predictions.csv
│ ├── Absenteeism_preprocessed.csv
│ └── High_Risk_Employees.csv
├── notebooks/ # Notebooks Jupyter du projet
│ ├── Absenteeism Exercise -Preprocessing.ipynb
│ ├── Absenteeism Exercise - Logistic Regression_prior to custom_scaler.ipynb
│ └── Absenteeism_predictions.ipynb
├── requirements.txt # Bibliothèques nécessaires
└── README.md # Présentation du projet


## 🔍 Contenu des notebooks

- **Preprocessing**  
  Nettoyage des données, transformation des variables (encodage one-hot), normalisation, et préparation pour le modèle.

- **Régression Logistique**  
  Construction du modèle prédictif, analyse de la pertinence des variables explicatives, évaluation des performances.

- **Prédictions**  
  Application du modèle sur de nouvelles données, génération des prédictions et identification des employés à haut risque.

## 🧪 Technologies & Méthodes

- Python 3
- Pandas et NumPy pour la manipulation des données
- Scikit-learn et StatsModels pour la modélisation
- Matplotlib pour les visualisations
- Régression logistique
- Encodage des variables catégorielles (One-hot encoding)
- Standardisation personnalisée

## ⚙️ Exécution du projet

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/mohammed-ouahhabi/absenteisme-prediction.git
   cd absenteisme-prediction

```bash
pip install -r requirements.txt

🎯 Objectif
Construire un modèle prédictif fiable permettant d’évaluer le risque d’absentéisme des employés et d’aider les entreprises à anticiper et gérer ce phénomène.

📊 Résultats attendus
-Données nettoyées et traitées

-Fichiers CSV contenant les prédictions

-Liste des employés identifiés comme à haut risque
