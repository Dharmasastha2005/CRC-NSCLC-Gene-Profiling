# CRC-NSCLC-Gene-Profiling
Exploratory transcriptomics and machine learning analysis of CRC and NSCLC gene expression data using GEO dataset GSE68086.

This repository contains a complete genomics analysis pipeline applied to colorectal cancer (CRC) and non-small cell lung cancer (NSCLC) samples using publicly available gene expression data from the GEO dataset GSE68086. The project is designed to showcase computational skills in bioinformatics and biomedical data science.

Key Features
Data Preprocessing & Quality Control
Load and clean the expression matrix.
Filter low-variance genes.
Apply log-transformation for normalization.

Exploratory Data Analysis
Generate boxplots and density plots to assess overall expression distribution.
Compute correlation heatmaps for sample similarity.
Perform PCA, t-SNE, and UMAP for dimensionality reduction and visualization of cancer vs. healthy groups.

Differential Expression Analysis
Identify genes significantly altered in CRC vs. Healthy and NSCLC vs. Healthy.
Perform statistical testing (t-test/Mann-Whitney).
Create volcano plots, heatmaps, and violin plots to highlight top genes.

Machine Learning Classification
Select significant features for training classifiers.
Build Random Forest and XGBoost models to distinguish cancer types from healthy samples.
Evaluate performance using ROC curves and AUC scores.

Why This Project Matters
This project demonstrates end-to-end competency in biomedical data analysis and computational genomics, combining statistical rigor, visualization, and machine learning. It can be used as a starting point for more advanced biomarker discovery and cancer classification research.

Technologies Used
Python: pandas, numpy, matplotlib, seaborn, scikit-learn, umap-learn
Jupyter Notebook / Google Colab for code execution and documentation.
