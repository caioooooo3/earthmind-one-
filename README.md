# EarthMind One — Dengue Risk Forecasting Prototype

EarthMind One is a **Data Science prototype** exploring the use of climate and epidemiological data to support dengue-risk analysis.

## Current status

**Work in progress.**

The repository currently contains the initial exploratory-analysis notebook:

~~~text
notebooks/01_data_exploration.ipynb
~~~

Earlier repository scaffolding included planned modules for data collection, feature engineering, modeling, prediction and dashboarding. Empty placeholder files are being removed so the public repository reflects only implemented work.

## Project direction

The intended workflow is:

~~~text
Climate + epidemiological data
            ↓
Data preparation
            ↓
Exploratory analysis
            ↓
Feature engineering
            ↓
Predictive modeling
            ↓
Risk visualization
~~~

## Next steps

- formalize and document the data sources;
- create a reproducible ingestion and cleaning pipeline;
- define the prediction target and baseline;
- train and evaluate predictive models;
- document metrics and model limitations;
- build a risk-visualization layer.

## Repository structure

~~~text
.
├── notebooks/
│   └── 01_data_exploration.ipynb
├── .gitignore
├── LICENSE
└── README.md
~~~

## Portfolio note

This repository is intentionally labeled as a prototype. Results, model performance and production-readiness will only be documented after they are implemented and validated.
