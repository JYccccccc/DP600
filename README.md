# DP600
# 📊 Analyse du E-commerce Brésilien avec Microsoft Fabric

Ce projet présente une analyse complète du célèbre dataset **Olist** à l'aide de **Microsoft Fabric**. Il comprend le traitement des données, le modeling sémantique, la modélisation en étoile, l'intégration dans Power BI, et la publication sur GitHub dans un format compatible avec le workflow Power BI Project (`.pbip`).

---

## 📁 Structure du projet
├── Files # Données sources (fichiers CSV du dataset Olist)  
├── docs # Documentation, rapports, schémas et rapport Power BI  
├── notebooks # Scripts de traitement et de modélisation (Microsoft Fabric Notebooks)  
└── README.md # Ce fichier de description du projet
---

## 🗂️ Détails des dossiers

### `Files/`
Contient les 9 fichiers CSV d’origine du dataset Olist :
- Données clients, produits, commandes, paiements, vendeurs, etc.

### `notebooks/`
Contient les notebooks utilisés pour :
- `ImportAndClean.ipynb` : importation, nettoyage et normalisation des données dans le Lakehouse
- `Modeling.ipynb` : création des tables dimensionnelles et de faits selon un schéma en étoile

### `docs/`

| Dossier/Fichier                                 | Description |
|-------------------------------------------------|-------------|
| `Brazilian E-Commerce.pbix`                     | 💡 Rapport Power BI complet (visualisations interactives) |
| `Brazilian E-Commerce.pbip/`                    | 📁 Structure du projet Power BI compatible Git (modèle sémantique + layout + visuels) |
| `Brazilian E-Commerce.SemanticModel/`           | 🔧 Définition du modèle sémantique Power BI (tables, relations, mesures) |
| `Brazilian E-Commerce.Report/`                  | 🎨 Configuration du rapport Power BI (fichiers JSON, ressources) |
| `Intégration des Données Olist avec Microsoft Fabric.pdf` | 📘 [Rapport PDF : Intégration des Données Olist avec Microsoft Fabric](docs/Intégration des Données Olist avec Microsoft Fabric.pdf) |
| `MCD.png`                                       | 🧩 Modèle conceptuel des données (modélisation en étoile) |

---

## ⭐ Objectifs du projet

1. **Importer et nettoyer les données** dans Microsoft Fabric (OneLake + Notebooks)
2. **Créer un modèle de données** structuré avec tables de faits et dimensions (SCD simulé)
3. **Construire un rapport Power BI interactif** sur les ventes, produits, clients, etc.
4. **Exporter et versionner le rapport** dans un dépôt GitHub (format `.pbip` recommandé)

---

## 🚀 Outils utilisés

- 📦 **Microsoft Fabric** (Lakehouse, Notebooks, Dataflows)
- 📊 **Power BI Desktop & Power BI Service**
- ☁️ **GitHub** pour la gestion du code source
- 🧪 **Python (PySpark)** pour le nettoyage et la transformation
- 🧱 **Modélisation en étoile** : `fact_orders`, `dim_customers`, `dim_products`, etc.

---

## 📌 Résultat attendu

Un rapport Power BI professionnel basé sur un pipeline complet dans Microsoft Fabric, prêt pour être présenté ou intégré dans un environnement de données d’entreprise.

---

## ✍️ Auteur

Projet réalisé dans le cadre d’un projet d’analyse de données avec Fabric et Power BI.  
Contact : [jiayin.chen@efrei.net]
