# BRSP-Week-2---Differential-Expression-Analysis-GEO2R-
# Differential Expression Analysis (GEO2R) - GSE41586

## Project Description
This repository contains a Differentially Expressed Genes (DEG) analysis report using the **GEO2R** web-based tool. The analysis was performed on a public transcriptomics dataset to understand cellular responses to specific treatments or infections.

## Dataset
- **Dataset ID:** [GSE41586](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE41586)
- **Platform:** GPL570 [HG-U133_Plus_2] Affymetrix Human Genome U133 Plus 2.0 Array.
- **Samples:** Human host cells (HT29/Macrophages) responding to bacterial stress.

## Methods
1. **Group Definition:** - **Healthy (Control):** 3 samples.
   - **Infected (Treated):** 6 samples.
2. **Analysis Parameters:**
   - Significance: Adjusted P-Value (Padj) < 0.05.
   - Correction Method: Benjamini & Hochberg (FDR).
3. **Reproducibility:** Consistency verified across top-ranked genes and multiple analysis iterations.

## Analysis Results

### 1. Sample Metadata & Grouping
<p align="center">
  <img src="overview-defines-group" width="800">
  <br>
  <b>Figure 1:</b> Overview of sample metadata and group definitions (Healthy vs Infected).
</p>

The following are the visualization results and key statistical data from the differential expression analysis of the GSE41586 dataset:
### 2. Volcano Plot Visualization
<p align="center">
  <img src="visualization-volcanoplot" width="600">
  <br>
  <b>Figure 2:</b> Volcano Plot showing significant up-regulated (red) and down-regulated (blue) genes in HT29 cells.
</p>

### 3. Top Differentially Expressed Genes (DEGs)
Based on statistical analysis, here are the top three genes with the highest significance levels:

| Gene Symbol | log2FoldChange | adj.P.Val | Biological Description |
| :--- | :---: | :---: | :--- |
| **ATF5** | -2.387 | 4.80e-51 | Activating transcription factor 5 (Down-regulated) |
| **PI3** | -3.621 | 2.21e-48 | Peptidase inhibitor 3 (Down-regulated) |
| **TRIM31** | 1.42 | 8.61e-48 | Tripartite motif containing 31 (Up-regulated) |

## Conclusion
The infection leads to a significant suppression of cellular survival genes such as **ATF5** and protease inhibitors like **PI3**, while triggering the up-regulation of immune-related genes like **TRIM31**. This indicates massive transcriptomic remodeling in the host cell.
