![Préparation des données pour un organisme de santé publique](https://github.com/Sengsathit/OCR_data_scientist_assets/blob/main/header_sante_publique_france.png?raw=true)

# PROJET : Préparation des données pour un organisme de santé publique

Ce projet consiste à analyser et nettoyer les données de la base **Open Food Facts**, utilisée par l'agence Santé publique France. Cette base open source contient des informations détaillées sur les produits alimentaires, comme leurs ingrédients, leur origine, et leurs qualités nutritionnelles. Elle est utilisée pour aider les consommateurs et les chercheurs à mieux comprendre la qualité nutritionnelle des aliments.

L'objectif principal est de préparer les données pour une application future permettant d'automatiser ou de suggérer des valeurs manquantes lors de l'ajout de nouveaux produits, afin de réduire les erreurs humaines et d'améliorer la complétude des données.

## Structure du dépôt

- `notebook.ipynb` : Notebook Jupyter contenant les étapes de préparation de données, de nettoyage des données, d'exploration des données et des visualisations associées.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter les notebooks.

---

## Prérequis

Pour exécuter ce projet, vous aurez besoin de Python (version 3.8 ou supérieure). Il est également recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.

### Étapes pour créer et activer un environnement virtuel :

1. Créez un environnement virtuel :
   ```bash
   python -m venv .venv
   source .venv/bin/activate

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
