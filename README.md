# TCGA BRCA RNA Analysis Project

# TCGA BRCA RNA Analysis Project

## Overview
This project analyzes RNA expression data from **The Cancer 
Genome Atlas (TCGA)** for breast cancer (BRCA). The goal is 
to identify genes associated with high- and low-risk patient 
groups, perform survival analysis, and generate insights on 
prognostic biomarkers.

## Features
- Data preprocessing and normalization of TCGA BRCA RNA-seq 
data
- Differential gene expression analysis between patient risk 
groups
- Kaplan-Meier survival analysis
- Cox proportional hazards modeling
- Visualizations including survival curves and expression 
heatmaps
- Generation of multi-gene prognostic signatures

## Files
- `TCGA_BRCA_R_Analysis_Project_Blair_Apr_7_2026.Rmd`: Main R 
Markdown file containing all analyses, code, and figures.
- `README.md`: Project overview and instructions.
- *(Optional: add any other data or scripts you include in 
the repo)*

## Requirements
- R (version ≥ 4.0)
- R packages: `survival`, `survminer`, `limma`, `ggplot2`, 
`dplyr`, `tidyr`, `ComplexHeatmap`, `TCGAbiolinks`  
*(Install missing packages using `install.packages()` or 
`BiocManager::install()` for Bioconductor packages)*

## How to Run
1. Clone the repository:
   ```bash
   git clone 
https://github.com/blairgsteele/Bioinformatics.git
