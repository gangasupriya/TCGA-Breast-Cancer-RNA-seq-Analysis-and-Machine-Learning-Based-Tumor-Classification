# TCGA Breast Cancer RNA-Seq Analysis & ML-Based Tumor Classification

Differential gene expression analysis and machine learning classification
using TCGA-BRCA RNA-Seq data, with interactive visualisation in Tableau.

## What it does
- Downloads TCGA-BRCA data using TCGAbiolinks (Primary Tumor vs Normal)
- Runs DESeq2 differential expression analysis
- Performs GO and KEGG pathway enrichment (clusterProfiler)
- Trains Random Forest classifier on top 500 variable genes
- Evaluates model with ROC-AUC, confusion matrix, feature importance
- Generates heatmap, volcano plot, PCA, MA plot in R
- Interactive volcano plot and expression visualisations in Tableau

## Tools & Technologies
- Language: R
- Libraries: TCGAbiolinks, DESeq2, clusterProfiler, randomForest,
  pROC, pheatmap, ggplot2, caret, org.Hs.eg.db
- Visualisation: Tableau (Book11.twbx)
- Data: TCGA-BRCA (Primary Tumor vs Solid Tissue Normal)

## Key Outputs
- DESeq2_Annotated_Results.csv
- GO_Enrichment.csv
- rf_predictions.csv
- gene_importance.csv
- ROC curve, heatmap, volcano plot, PCA plot
- Tableau dashboard (Book11.twbx)




