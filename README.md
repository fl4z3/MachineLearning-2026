# Progetto Machine Learning 2026

Progetto per l'esame di Fondamenti e Applicazioni del Machine Learning.

Dataset assegnato: [MOOC User Action Dataset](https://snap.stanford.edu/data/act-mooc.html) (Stanford SNAP).

## Struttura repository

- `data/` — dataset originali e file `manuale.csv` / `training.csv`
- `notebooks/` — notebook Jupyter con l'analisi e i classificatori
- `src/` — eventuale codice Python riutilizzabile

## Setup dataset

I file `.tsv` originali non sono versionati su git (troppo pesanti). Scaricarli da
[snap.stanford.edu/data/act-mooc.html](https://snap.stanford.edu/data/act-mooc.html) ed estrarre
`mooc_actions.tsv`, `mooc_action_features.tsv`, `mooc_action_labels.tsv` dentro la cartella `data/`.
