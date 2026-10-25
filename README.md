# Atelier Python pour l'analyse de données (M1-INF4)

Notebooks from the M1-INF4 workshop (Master MIAGE, Paris 1 Panthéon-Sorbonne), going from a Python refresher to a full data integration case study.

## Getting set up

```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
source .venv/bin/activate   # macOS/Linux
pip install -r requirements.txt
```

Open the notebooks from inside `notebooks/` — the relative paths to `data/` assume that's your working directory.

## The sessions

1. [Python & NumPy essentials](notebooks/01-Python-NumPy.ipynb) — variables, lists, dicts, then NumPy arrays, indexing and vectorized operations.
2. [Pandas manipulation](notebooks/02-Pandas-Manipulation-S2.ipynb) — selecting, filtering, sorting and `groupby`, on the homelessness and sales_subset datasets.
3. [Data cleaning](notebooks/03-Data-Cleaning-S3.ipynb) — auditing missing values, standardising text/numbers/dates, duplicates, and a reproducible cleaning pipeline on temperature data.
4. [EDA & visualization](notebooks/04-EDA-Visualization-S4.ipynb) — the six chart types (bar, line, histogram, boxplot, scatter, heatmap) plus checked joins, on support ticket data.
5. [Data integration case study](notebooks/05-Data-Integration-Case-Study.ipynb) — the final group project: clean, join and compare store sales for a fictional retailer to check a manager's claim.

Each notebook expects the matching CSVs in `data/` (already included here).

## Session 5 — group project (G03)

This one's the graded deliverable, split across the group:

- **Done:** source audit (section 1), cleaning (section 2), joins + reconciliation (section 3).
- **Still open:** interpretation for section 2, then indicators, the three figures, the decision brief and the export (sections 4-7).

Group members and who did what: *complete here.*

Outputs (summary tables, exported figures) land in `notebooks/case_study_outputs/` once the export section is filled in — that folder isn't tracked here since it's generated, not written by hand.
