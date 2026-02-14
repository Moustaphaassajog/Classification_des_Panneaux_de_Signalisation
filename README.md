# Classification des Panneaux de Signalisation avec CNN
## 📌Description
Ce projet consiste à développer un modèle de Deep Learning basé sur un réseau de neurones convolutionnel (CNN) pour la classification automatique des panneaux de signalisation.L’objectif est de reconnaître correctement 58 types de panneaux routiers à partir d’images redimensionnées en 32×32 pixels.
## 🎯Objectifs
-Charger et prétraiter un dataset d’images de panneaux

-Construire une architecture CNN adaptée

-Entraîner le modèle sur les données d’apprentissage

-Évaluer les performances à l’aide de métriques adaptées

-Analyser les résultats (accuracy, loss, matrice de confusion)
## 📂 Dataset
-Source:https://www.kaggle.com/datasets/ahemateja19bec1025/traffic-sign-dataset-classification/data

-58 classes différentes

-Images redimensionnées en 32×32 pixels

-Encodage des labels en One-Hot Encoding

## ⚙️ Méthodologie

- 1.Chargement des données

- 2.Prétraitement (redimensionnement, normalisation)

- 3.Encodage des labels

- 4.Split train / validation

- 5.Construction du modèle CNN

- 6.Entraînement

- 7.Évaluation des performances

## 🧠 Architecture du Modèle

Le modèle CNN est composé de :

### - 3 blocs convolutionnels :

  #### Conv2D

  #### BatchNormalization

  #### MaxPooling

  #### Dropout

### - Partie Fully Connected :

  #### Dense 256

  #### Dense 128

  #### Dense 58 (Softmax)

## 📊 Évaluation

Les performances du modèle sont mesurées à l’aide de :

- Accuracy

- Loss

- Matrice de confusion

- Courbes d’apprentissage (Accuracy & Loss)

#### 🛠️ Technologies utilisées

- Python

- TensorFlow / Keras

- NumPy

- Matplotlib

- Scikit-learn

## 🚀 Résultats

Le modèle permet de classifier efficacement les panneaux de signalisation et démontre l’efficacité des CNN pour les tâches de vision par ordinateur.
