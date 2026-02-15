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

### Analysis Results

#### Volcano Plot
![Volcano Plot](Screenshot%202026-02-15%20at%2021.39.20.png)
*Figure 1: Distribution of up-regulated (red) and down-regulated (blue) genes.*

### Top Differentially Expressed Genes
| Gene Symbol | log2FoldChange | adj.P.Val | Description |
|-------------|----------------|-----------|-------------|
| **ATF5** | -2.387         | 4.80e-51  | Down-regulated |
| **PI3** | -3.621         | 2.21e-48  | Down-regulated |
| **TRIM31** | 1.42           | 8.61e-48  | Up-regulated   |

## Conclusion
The infection leads to a significant suppression of cellular survival genes such as **ATF5** and protease inhibitors like **PI3**, while triggering the up-regulation of immune-related genes like **TRIM31**. This indicates massive transcriptomic remodeling in the host cell.

---
*Assignment for Bioinformatics Course / IPSF Global Research Lab*
