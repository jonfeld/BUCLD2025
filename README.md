# BUCLD2025: Disfluency and Fluency Clustering in Bilingual Child Speech

This repository accompanies our BUCLD 2025 submission. It contains the analysis pipeline for examining disfluency patterns in bilingual children's speech using the Paradis corpus.

## Overview

The notebook extracts and analyzes:

- Disfluencies (pauses, fillers, self-corrections)
- Complexity metrics (MLU, TTR, speech rate)
- Fluency comparisons by gender, L1 background, and age
- KMeans clustering of fluency profiles

## Directory Structure

BUCLD2025/
├── bucld_notebook.ipynb # Main analysis notebook
├── Paradis-20250805T021057Z-1-001.zip # Zipped dataset (CHA files + metadata)
├── abstract.pdf # BUCLD 2025 abstract
├── requirements.txt
├── README.md
├── .gitignore

## Dataset

Unzip `Paradis-20250805T021057Z-1-001.zip` in the project root. It contains:

> The dataset is accessed locally (e.g., via Google Drive) and is not committed to the repo.

## Notebook

`bucld_notebook.ipynb` runs the full analysis:

- Processes `.cha` files
- Computes fluency and complexity metrics
- Merges metadata
- Performs statistical analysis and clustering
- Generates plots and summary tables

## Setup

To install dependencies:

```bash
pip install -r requirements.txt
```