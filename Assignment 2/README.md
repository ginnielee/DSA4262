# DSA4262 Individual Assignment 2 — Dreaddit Stress Detection

This repo contains a reproducible Jupyter Notebook for detecting stress in Reddit posts (Dreaddit) and additional analyses on cross-subreddit generalization, dialect markers, and failure modes.

## Repo structure
- `notebooks/DSA4262_2.ipynb` — main notebook (run top-to-bottom)
- `data/` — dataset files (see below)
- `requirements.txt` — Python dependencies

## Data
Place the following files in the `data/` folder:
- `dreaddit-train.csv`
- `dreaddit-test.csv`

> If the dataset is restricted, do not commit the CSVs to GitHub. Instead, download from the course source and place them locally in `data/`.

## Setup
Create and activate a virtual environment (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt