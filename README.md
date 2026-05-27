# Rice Arsenic Transcriptomics Analysis

## Objective
Transcriptomics analysis of arsenic-stressed rice roots using GEO RNA-seq expression data and Python.

## Dataset
- GEO Accession: GSE36696
- Organism: Oryza sativa
- Stress Condition: Arsenic treatment

## Workflow
1. Downloaded GEO RNA-seq expression data
2. Extracted control and arsenic-treated root samples
3. Loaded expression matrices using pandas
4. Merged transcriptomics datasets
5. Calculated fold change and log2 fold change
6. Identified upregulated and downregulated genes
7. Generated volcano-style DEG visualization

## Tools Used
- Python
- pandas
- numpy
- matplotlib
- GEO/NCBI datasets

## Output Files
- rice_transcriptome_results.csv
- upregulated_genes.csv
- downregulated_genes.csv
- rice_arsenic_volcano_plot.png

## Visualization

![Volcano Plot](rice_arsenic_volcano_plot.png)

## Author
Srishti Singh
