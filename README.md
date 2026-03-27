# 📊 Étude Comparative des Algorithmes de Machine Learning Supervisé

## 👨‍🎓 Réalisé par
- **Taha Cherraj**
- **Marouane Senhaji**

## 👨‍🏫 Encadré par
**Monsieur Larhlimi**  
ENCG Settat

---

## 📚 Sommaire

1. Introduction  
2. Problématique  
3. Présentation des algorithmes  
4. Méthodologie  
5. Implémentation (Google Colab)  
6. Résultats et analyse  
7. Discussion  
8. Conclusion  

---

## 📌 Introduction

Dans un contexte marqué par l’explosion des données et l’importance croissante de l’intelligence artificielle, le machine learning supervisé s’impose comme un outil essentiel pour la prise de décision. Ce projet s’inscrit dans une démarche d’analyse et de comparaison de plusieurs algorithmes de classification afin d’identifier le modèle le plus performant selon la nature des données.

L’objectif est de comprendre comment différents modèles réagissent face à des datasets variés, tout en mettant en évidence leurs forces, leurs limites et leurs conditions optimales d’utilisation.

---

## ❓ Problématique

**Comment choisir et optimiser un algorithme de machine learning supervisé afin d’obtenir les meilleures performances de prédiction selon la nature des données, tout en évitant le surapprentissage et en garantissant une bonne généralisation ?**

---

## 🎯 Objectifs

- Comparer plusieurs algorithmes de machine learning supervisé
- Évaluer leurs performances sur différents datasets
- Identifier le modèle le plus adapté selon le contexte
- Analyser les risques d’overfitting
- Optimiser les paramètres pour améliorer les résultats

---


## 🤖 Présentation des Algorithmes

Dans ce projet, plusieurs modèles de classification supervisée ont été utilisés :

### 🔹 Logistic Regression
Modèle statistique simple utilisé pour les problèmes de classification binaire.

### 🔹 K-Nearest Neighbors (KNN)
Algorithme basé sur la similarité entre les données.

### 🔹 Support Vector Machine (SVM)
Modèle puissant qui cherche à maximiser la marge entre les classes.

### 🔹 Random Forest
Méthode d’ensemble basée sur plusieurs arbres de décision pour améliorer la précision.

---

## ⚙️ Méthodologie

Le projet suit les étapes suivantes :

1. Chargement des datasets (ex: Iris, Breast Cancer)
2. Prétraitement des données
3. Division en données d'entraînement et de test
4. Entraînement des modèles
5. Évaluation des performances (accuracy, etc.)
6. Comparaison des résultats

---

## 💻 Implémentation

L’ensemble du travail a été réalisé sur **Google Colab** en utilisant Python et des bibliothèques telles que :

- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

---

## 📊 Résultats et Analyse

Les résultats obtenus montrent que :

- Certains modèles comme **Random Forest** offrent de très bonnes performances globales
- Les modèles simples comme **Logistic Regression** restent efficaces sur des données linéaires
- Le choix du modèle dépend fortement de la structure du dataset
- L’overfitting peut apparaître si les modèles ne sont pas correctement réglés

---

## 🧠 Discussion

Il est important de noter qu’il n’existe pas de modèle universellement meilleur. Selon le **No Free Lunch Theorem**, aucun algorithme ne domine dans tous les cas.

Ainsi, le choix du modèle doit prendre en compte :
- La nature des données
- Le volume des données
- Le besoin en précision
- La complexité du problème

---

## 🏁 Conclusion

Ce projet a permis de mettre en évidence l’importance du choix des algorithmes en machine learning supervisé. À travers une approche comparative, nous avons démontré que chaque modèle possède ses spécificités et que leur performance dépend fortement du contexte d’utilisation.

Une bonne compréhension des données et un ajustement des paramètres sont essentiels pour garantir des résultats fiables et pertinents.

---

## 🚀 Perspectives

- Tester d’autres algorithmes (XGBoost, Neural Networks)
- Optimiser les hyperparamètres
- Utiliser des datasets plus complexes
- Implémenter des techniques de validation croisée

---

## 📎 Lien du Notebook

👉 (https://colab.research.google.com/github/cherrajtahaencg-beep/S8-CI-21008894/blob/main/cherraj_taha_ci.ipynb)

---

## ⭐ Remerciements

Nous remercions **Monsieur Larhlimi** pour son encadrement et son accompagnement tout au long de ce projet.
