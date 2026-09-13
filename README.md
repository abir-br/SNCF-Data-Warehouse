# SNCF Data Warehouse & Business Intelligence

Projet de conception d’un Data Warehouse pour analyser les ventes de billets et abonnements de la SNCF et faciliter la prise de décision.

## Objectifs

- Analyser les ventes et le chiffre d’affaires
- Suivre la ponctualité et les performances
- Étudier l’impact des promotions
- Identifier des KPI utiles à la prise de décision

## Modèle de données

Conception d’un **modèle en étoile** avec :

- Client
- Temps
- Trajet
- Train
- Promotion
- Canal
- Table de faits : ventes

## Analyses

Exemples de KPI et requêtes :

- Chiffre d’affaires par ligne et par mois
- Nombre de billets vendus
- Nombre d’abonnements
- Performance des canaux de vente
- Impact des promotions
- Taux de ponctualité des trains
- Coûts de maintenance

## Technologies / notions

- Data Warehouse
- Data Mart
- Modélisation dimensionnelle
- Schéma en étoile (Star Schema)
- KPI
- Analyse multidimensionnelle
- SQL / requêtes analytiques

## Architecture

```text
Données métier
     ↓
Data Warehouse
     ↓
Data Mart "Ventes"
     ↓
Modèle en étoile
     ↓
KPI & analyses
     ↓
Prise de décision
```
