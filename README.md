# Final Project Reproducibility Report

This repository contains the reproducibility materials for my final project on missing data handling and survival prediction in NSCLC.

## Main file
- `FinalWrittenReport.qmd`

## Output files
- `FinalWrittenReport.html`
- `FinalWrittenReport.docx`

## Folder structure
- `datasets/`: cleaned datasets and risk-score datasets
- `figures/`: figures used in the report
- `tables/`: summary and result tables
- `models/`: fitted model objects and imputation objects

## Data source
The project reads public MSK-CHORD data directly from online sources.

## Reproducibility
To reproduce the report, render:

```bash
quarto render FinalWrittenReport.qmd
