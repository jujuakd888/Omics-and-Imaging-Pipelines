# Omics-and-Imaging-Pipelines
Built a reproducible R Markdown pipeline (tidyverse, ggplot2, pheatmap, survival) to analyse TCGA-style breast cancer data: tumour-vs-normal testing (Wilcoxon + FDR), heatmaps, volcano plots, and Kaplan–Meier curves; delivered cleaned CSV outputs and figures to a shared GitHub repo.
# Omics-and-Imaging-Pipelines

This repository contains demo RMarkdown pipelines for bioinformatics and imaging analysis.  
The code is designed to be **lightweight, reproducible, and educational**, showcasing skills in `R`, `ggplot2`, `pheatmap`, and survival analysis.

---

## Contents
Omics-and-Imaging-Pipelines-GITHUB/
├── data/ # toy_expression.csv, toy_phenotype.csv (runs instantly)
├── notebooks/ # RMarkdown pipeline(s)
│ └── Omics-and-Imaging-Pipelines.Rmd
├── R/ # helper scripts (optional)
├── figs/ # auto-saved plots
├── README.md # this file


---

## How to Run
1. Clone or download this repo.  
2. Open `notebooks/Omics-and-Imaging-Pipelines.Rmd` in **RStudio**.  
3. Click **Knit**.  
   - By default, runs instantly on the **toy dataset** (`data/toy_expression.csv`, `data/toy_phenotype.csv`).  
   - To use full TCGA datasets, replace `expr_file` and `pheno_file` paths with downloads from **UCSC Xena**.  

---

## Features
- Tumor vs Normal comparison  
- Heatmap of expression  
- Volcano plot  
- Kaplan–Meier survival curves  

---

## Author
**Jude Akkad**  
MSc Stem Cell & Regenerative Therapies — King’s College London  
LinkedIn: [Jude Akkad](https://linkedin.com/in/judeakkad)  
