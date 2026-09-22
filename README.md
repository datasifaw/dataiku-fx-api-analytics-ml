# Projet FX Analytics — MAD / EUR / USD avec Dataiku

## Frankfurter API • Analytics • Machine Learning • Automatisation

## Contexte

Ce projet consiste à construire un pipeline Dataiku de bout en bout
à partir de données de taux de change récupérées depuis la Frankfurter API.

L'analyse est principalement centrée sur trois devises :

- MAD — Dirham marocain
- EUR — Euro
- USD — Dollar américain

L'objectif est d'étudier notamment l'évolution du dirham marocain
face à l'euro et au dollar, puis d'exploiter ces données pour réaliser
des analyses, des visualisations et des modèles de Machine Learning.

## Objectifs du projet

Le projet couvre :

- ingestion de données depuis une API REST
- manipulation de données JSON
- collecte de données historiques FX
- préparation et nettoyage dans Dataiku
- création de variables temporelles
- calcul de KPI financiers
- création d'un dashboard
- détection d'anomalies
- prévision de séries temporelles
- scoring
- automatisation avec Dataiku Scenarios
- versionnement du projet avec Git / GitHub


## Paires de devises étudiées

### EUR / MAD

Analyse de l'évolution de l'euro par rapport au dirham marocain.

Exemple :

1 EUR → MAD

### USD / MAD

Analyse de l'évolution du dollar américain par rapport au dirham marocain.

Exemple :

1 USD → MAD

### EUR / USD

Analyse complémentaire permettant de comparer les deux principales
devises internationales utilisées dans le projet.

## Source de données

Les taux de change sont récupérés avec la Frankfurter API.

Exemples d'appels API :

### EUR vers MAD


https://api.frankfurter.dev/v2/rate/eur/mad

{
  "date": "2026-09-22",
  "base": "EUR",
  "quote": "MAD",
  "rate": 10.9335
}

USD vers MAD
https://api.frankfurter.dev/v2/rate/usd/mad

{
  "date": "2026-09-22",
  "base": "USD",
  "quote": "MAD",
  "rate": 9.5239
}

