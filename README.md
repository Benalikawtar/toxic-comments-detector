# 🧠 Toxic Comment Detection – Deep Learning Project

Ce projet applique le Deep Learning au traitement automatique de la toxicité dans les commentaires textuels. Il met en œuvre un modèle de classification entraîné sur des commentaires annotés, pour distinguer les propos toxiques des propos neutres.

## 🎯 Objectif

Développer un système de détection automatique des commentaires toxiques à partir de textes en langage naturel, basé sur un réseau de neurones.

## 🔧 Méthodologie

- Prétraitement des textes : nettoyage, vectorisation, padding
- Construction d’un modèle séquentiel (Keras)
- Entraînement supervisé sur un jeu de données annoté
- Sauvegarde et export du modèle (`toxicity.h5`)
- Évaluation à l’aide des métriques classiques **précision**, **rappel** , **loss**

## 🗃️ Structure du projet

- `deepLproject.ipynb` : notebook principal avec tout le pipeline NLP + entraînement
- `toxicity.h5` : modèle sauvegardé au format Keras
- `requirements.txt` : bibliothèques Python utilisées

## 🛠️ Technologies utilisées

- **Python 3**
- **Keras / TensorFlow**
- **scikit-learn**
- **NumPy / Pandas**
- **Jupyter Notebook**

