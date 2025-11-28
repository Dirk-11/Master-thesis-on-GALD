# Master-thesis-on-GALD

This repository contains the analysis scripts, results, and figures generated for my Master’s thesis on **Gestational Alloimmune Liver Disease (GALD)**.  
The project investigates maternal plasma proteomics and IgG–fetal liver antigen interactions to explore biological differences between **GALD** and **Control** groups.

This repository contains all analyses performed to:

- Compare plasma proteomes of GALD vs Control groups
- Identify proteins and peptides that are unique or enriched in GALD  
- Analyze IgG–fetal liver antigen immunoprecipitation datasets  
- Perform differential abundance testing (limma)  
- Run gene-set enrichment (FGSEA) and pathway clustering  
- Generate reproducible figures for scientific reporting

## Repository Structure

R scripts in one folder
Tables / processed data I used for generating my results
Final results for my thesis

## Reproducing the Analysis

Raw mass spectrometry data and maxquant output files such as original.tsv and evidence.txt are stored on BOX and belong to:
Proteomics Research Infrastructure (PRI), Copenhagen University Hospital.
These data are not publicly available.

1. Create the environment:

```bash
conda env create -f thesis_environment.yaml
conda activate thesis


