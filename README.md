# Final Project Reproducibility Report

This repository contains the reproducibility materials for my final project on missing data handling and survival prediction in non-small cell lung cancer (NSCLC).

## Main files

- `final_project_reproducibility.qmd`: source file for the reproducibility report
- `final_project_reproducibility.html`: rendered HTML version
- `final_project_reproducibility.docx`: rendered Word version

## Supporting folders

- `final_project_reproducibility_files/`: auxiliary files generated during HTML rendering
- `datasets/`: cleaned datasets and datasets with risk scores
- `figures/`: figures used in the report
- `tables/`: summary tables and result tables
- `models/`: fitted model objects and imputation objects

## Project summary

This project examines how different missing-data strategies affect survival prediction in NSCLC. Three approaches are compared:

- complete-case analysis
- simple imputation
- multiple imputation by chained equations (MICE)

The analysis focuses on predictive discrimination, coefficient stability, and risk stratification under different missing-data handling methods.

## Data source

The analysis reads public MSK-CHORD data from online sources rather than relying on local raw data files.

## Reproducibility

To reproduce the report, render the Quarto file:

```bash
quarto render final_project_reproducibility.qmd --to html
quarto render final_project_reproducibility.qmd --to docx
