# Analyse des Ventes au Détail avec Power BI

## Présentation du Projet
Ce projet est un rapport de Business Intelligence complet réalisé dans le cadre de nos études à la Faculté Polydisciplinaire de Taroudant (Université Ibnou Zohr). 

L'objectif est de construire un tableau de bord interactif pour analyser les ventes au détail, comparer les performances réelles par rapport au budget, et utiliser les fonctionnalités d'Intelligence Artificielle de Power BI.

## Technologies Utilisées
*   **Base de données :** PostgreSQL
*   **ETL / Préparation :** Pentaho Data Integration (Spoon)
*   **Business Intelligence :** Power BI Desktop & Service
*   **Langages :** DAX (Data Analysis Expressions), M (Power Query)

## Architecture du Projet

Le projet est divisé en trois phases distinctes :

### Phase 1 : Analyse des Ventes Réelles
*   Importation des données CSV vers PostgreSQL via Pentaho.
*   Connexion de Power BI à la base de données PostgreSQL.
*   **Modélisation en étoile (Star Schema) :** Création des tables `fact_sales`, `dim_customer`, `dim_product` et `dim_date`.
*   Création de KPIs (Chiffre d'affaires, Quantité vendue, Panier moyen, etc.).

### Phase 2 : Analyse Budget vs Réel
*   Intégration des données budgétaires (Excel).
*   Transformation dans Power Query (Dépivotage des colonnes mensuelles).
*   Modélisation des relations entre le budget et les ventes réelles.
*   Création de mesures DAX pour calculer les écarts (Absolus et %).

### Phase 3 : Analyse Automatisée & IA
*   **Smart Narrative :** Génération automatique de résumés textuels des tendances.
*   **Q&A Visual :** Interaction en langage naturel avec les données.
