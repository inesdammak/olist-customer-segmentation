# 🛒 Olist — Segmentation Client, Scoring & Marketing Prédictif

Projet réalisé dans le cadre du MSc Manager in Data Marketing (INSEEC).

## 🎯 Contexte

Olist est une plateforme brésilienne qui connecte des petits commerçants aux
grandes marketplaces. Ce projet vise à exploiter les données de commandes,
clients et produits d'Olist pour construire une segmentation client, un
scoring de priorisation marketing, et des recommandations d'activation par
segment.

## 📂 Contenu du notebook

Le notebook suit une démarche data-driven en plusieurs étapes :

1. Préparation de l'environnement
2. Contexte business & cadrage du problème
3. Compréhension & exploration des données
4. Nettoyage & préparation des données
5. Analyse exploratoire (EDA)
6. Feature engineering — construction de la table client
7. Indicateurs marketing — modèle RFM (Récence, Fréquence, Montant)
8. Segmentation client par clustering (K-Means)
9. Scoring client — priorisation des cibles
10. Interprétation métier des segments
11. Fiches personas & plan d'activation marketing
12. Analyse de stabilité des segments
13. Conclusion stratégique

## 🗂️ Données

Le projet utilise le jeu de données public **Olist Brazilian E-Commerce**,
disponible sur Kaggle :
👉 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Les fichiers de données ne sont pas inclus dans ce dépôt (voir `.gitignore`).
Pour reproduire l'analyse, télécharge le dataset depuis Kaggle et place les
fichiers CSV dans un dossier `data/` à la racine du projet.

## 🛠️ Installation

```bash
git clone https://github.com/TON_USER/olist-scoring-marketing-predictif.git
cd olist-scoring-marketing-predictif
pip install -r requirements.txt
```

Puis lance Jupyter :

```bash
jupyter notebook notebooks/Olist_Scoring_Marketing_Predictif.ipynb
```

## 📦 Stack technique

- Python (pandas, numpy)
- Visualisation : matplotlib, seaborn, yellowbrick
- Machine Learning : scikit-learn (K-Means, standardisation, etc.)

## 🏆 Résultats clés

- Identification de segments clients actionnables via RFM + clustering
- Score de priorisation pour cibler les campagnes marketing
- Personas et recommandations d'activation par segment

## ✍️ Auteur

Projet académique — MSc Manager in Data Marketing, INSEEC.
