# 🏘️ Analyse du Marché Immobilier

## 📖 Description du Projet
Ce projet vise à anae lyser les tendances des ventes immobilières en explorant les caractéristiques des propriétés, les profils des clients et les performances des régions. L'objectif est d'identifier des opportunités stratégiques pour maximiser les ventes et la satisfaction des clients.

Ce travail inclut :
  -Une analyse complète des données clients et propriétés.
  -Des visualisations interactives pour présenter les résultats clés.
  -Des recommandations basées sur des insights tirés des données.

## 📂 Structure des données
### 🗂️ Fichiers utilisés :
1 . customers.csv 🧑‍🤝‍🧑
   - Informations sur les clients :
      - Clés principales : customerid, name, birth_date, sex, country, state, purpose,                  deal_satisfaction, mortgage, source.
2 . properties.csv 🏢
  - Détails des propriétés et des transactions :
      - Clés principales : id, building, date_sale, type, area, price, status, customerid.

📊 Jeu de données final :
  - Nombre total d'enregistrements : 267 lignes et 19 colonnes.

3. 🧹 Transformations effectuées :
- Fusion des deux fichiers sur customerid.
- Nettoyage des valeurs manquantes et anomalies.
- Création de nouvelles colonnes :
    - age_at_purchase : Âge au moment de l'achat.
    - price_interval : Catégories de prix.
    - year_sale : Année de vente.
  
## Fonctionnalités Principales
- Analyse descriptive : Exploration des ventes par région, type de bâtiment et profil des clients.
  
- Segmentation des âges et des prix : Identification des groupes d'acheteurs et des gammes de prix performantes.

## 🔍 Analyse effectuée
### Visualisations :
  - Répartition des ventes par âges des clients.
  - Chiffre d'affaires annuel.
  - Satisfaction des transactions par pays.
  - Performances des états et des bâtiments.
  - Répartition des ventes par état (USA).
  - Distribution des achats par âge et par prix.

- Recommandations stratégiques : Propositions pour maximiser les revenus et optimiser la stratégie marketing.

## 🛠️ Outils et technologies
  - 🔤 Langages : Python (Pandas, NumPy, Matplotlib, Seaborn).
  - 🧹 Traitement des données : Nettoyage, valeurs manquantes, dérivation de variables.
  - 🎨 Visualisation : Matplotlib et Seaborn.

## 🚀 Utilisation
## 🔧 Installation :
Assurez-vous d'avoir **Python 3.x** installé. Installez les dépendances :
```bash
pip install pandas numpy matplotlib seaborn
```

## ▶️ Exécution :
1. Placez les fichiers customers.csv et properties.csv dans le même répertoire que le script.
2. Lancez le script principal :
```bash
python real_estate_analysis.py
```

3. Consultez les visualisations et rapports générés dans le répertoire de sortie.

## Vidéo Explicative
Une vidéo détaillant le projet est disponible ici.

https://github.com/user-attachments/assets/90a9a107-546d-4243-9802-8e31566902bc
