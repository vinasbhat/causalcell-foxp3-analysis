# causalcell-foxp3-analysis
Exploring transcriptional changes following FOXP3 perturbation in human T cells using Python and public CRISPR datasets.

### Overview

This project explores how computational analysis can be used to analyse a published CRISPR perturbation dataset to understand how knocking out the transcription factor FOXP3 affects downstream gene expression.

## Dataset
This analysis uses publicly available supplementary data from:

Marson A. et al. (Nature, 2022)

The dataset contains CRISPR perturbation experiments in primary human T cells with differential gene expression results for multiple transcription factor knockouts.

Specifically, this notebook analyzes the supplementary differential expression table (Supplementary Table S4 / mmc5.xlsx), focusing on the FOXP3 knockout.
Paper- https://pmc.ncbi.nlm.nih.gov/articles/PMC11605694/

## Methods

- Python
- Pandas
- Matplotlib
- Exploratory data analysis
- Differential expression filtering (`padj < 0.05`)

---

## Results

- Loaded a real CRISPR perturbation dataset
- Filtered for FOXP3 knockout experiments
- Identified significantly affected genes
- Visualized transcriptional changes following FOXP3 perturbation

---

## Future Work

This project is an initial step toward integrating perturbation experiments, regulatory DNA activity, and protein interaction networks to reconstruct the causal regulatory logic governing T-cell state transitions.
