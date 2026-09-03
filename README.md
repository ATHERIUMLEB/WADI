# Prévision du niveau du réservoir (WADI)

Projet d'apprentissage : prédire le niveau futur d'un réservoir d'eau à partir des données SCADA du banc d'essai WADI.

## Arborescence

```
my_wadi/
├── README.md                          ← vous êtes ici
├── requirements.txt
├── wadi_reservoir_forecasting.ipynb   ← notebook principal
├── WADI_14days_new.csv                ← dataset (14 jours, 1 min)
└── docs/
    ├── design_doc.md                  ← DESIGN DOC CENTRAL
    ├── guide/                         ← explications pédagogiques
    └── rapport/                       ← livrables d'analyse
```


## Démarrage rapide

```bash
cd my_wadi
pip install -r requirements.txt
jupyter notebook wadi_reservoir_forecasting.ipynb
```

*(Option : utiliser un environnement virtuel `python3 -m venv .venv` pour isoler les dépendances.)*

## Objectif en une phrase

> Prédire le niveau du réservoir principal (`2_LT_001_PV`) dans **10 minutes** pour anticiper les débordements et optimiser le pompage.

## But du projet

 l'objectif n'est pas seulement d'obtenir le meilleur score, mais de **comprendre** chaque étape du pipeline et chaque modèle testé.
