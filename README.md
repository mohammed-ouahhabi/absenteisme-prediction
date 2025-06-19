# Prédiction de l'Absentéisme

Ce projet vise à analyser, préparer, prédire et visualiser l'absentéisme des employés à partir d'un jeu de données RH, en utilisant des techniques de régression logistique et de traitement des données.

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

- **Preprocessing** : Nettoyage, normalisation, transformation des variables (dont le one-hot encoding).
- **Régression logistique** : Construction et ajustement du modèle prédictif.
- **Prédictions finales** : Application du modèle, génération des résultats, et export des employés à haut risque.

## ⚙️ Installation

Pour exécuter ce projet, assurez-vous d’avoir Python 3 et installez les dépendances avec :

```bash
pip install -r requirements.txt

🧠 Objectif
Ce projet est conçu dans le cadre d'une étude pratique visant à prédire le comportement d’absentéisme en entreprise et identifier les profils à risque.

✨ Résultat attendu
Des fichiers CSV contenant les prédictions, ainsi qu’un rapport des employés présentant un risque élevé d’absentéisme.
