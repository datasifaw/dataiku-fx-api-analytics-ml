# Projet FX Analytics avec Dataiku

## Frankfurter API, Analytics, Machine Learning et automatisation

## Contexte

L'objectif de ce projet est de construire un pipeline Dataiku complet
à partir de données de taux de change récupérées depuis une API publique.

Le projet couvre :

- ingestion d'une API REST
- traitement de données JSON
- préparation et nettoyage
- analyse de séries temporelles
- calcul de KPI
- création d'un dashboard
- Machine Learning
- détection d'anomalies
- prévision de taux de change
- automatisation avec Dataiku Scenarios

## Architecture

Frankfurter API
↓
JSON
↓
Dataiku
↓
Data Preparation
↓
Historique FX
↓
Features temporelles
↓
KPI / Analytics
↓
Dashboard
↓
Machine Learning
↙                ↘
Anomalies        Forecasting
↓
Scoring
↓
Scenario Dataiku

## Devises étudiées

Le projet pourra notamment analyser :

- EUR / USD
- EUR / GBP
- EUR / INR
- EUR / JPY

## Analytics

Les indicateurs étudiés incluront :

- taux actuel
- variation quotidienne
- variation en pourcentage
- minimum
- maximum
- moyenne
- moyenne mobile
- volatilité
- évolution historique

## Machine Learning

### Détection d'anomalies

Identifier les journées présentant des variations inhabituelles
des taux de change.

### Forecasting

Construire un modèle de séries temporelles pour prévoir
l'évolution future d'un taux de change.

## Automatisation

Un Scenario Dataiku permettra d'automatiser :

API
↓
Mise à jour des données
↓
Préparation
↓
Calcul des KPI
↓
Machine Learning / Scoring
↓
Mise à jour du dashboard

## Technologies

- Dataiku
- Frankfurter API
- REST API
- JSON
- Visual Recipes
- Python
- Time Series
- Machine Learning
- Forecasting
- Dataiku Scenarios
- Dataiku Dashboards
