# Final Project — Diabetes (Chishan)

## Goal
A fully reproducible analysis that still renders if the data change slightly (e.g., removing a row).
This repo contains the Quarto report, code, and minimal instructions to reproduce all results.

---

## Data
- Dataset: `diabetes.rda` from the course GitHub materials.
- **Where to place it:** put `diabetes.rda` in the **project root** (the same folder as `report.qmd`).
- If you cannot share the data publicly, do **not** commit it; just place it locally as above and render.

**Variables (as used in the report):**
`pregnancy_num`, `glucose_mg-dl` (renamed to `glucose`), `dbp_mm-hg` (renamed to `dbp`), `triceps_mm`,
`insulin_microiu-ml` (renamed to `insulin`), `bmi`, `pedigree`, `age`, and 5-year status `diabetes_5y` (pos/neg).

---

## Requirements
- R (4.x recommended) and RStudio (or the Quarto CLI)
- Quarto (bundled with recent RStudio)
- R packages (install once):
  ```r
  install.packages(c("here","dplyr","ggplot2","readr","gtsummary","broom"))
