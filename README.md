# Cancer-Gene-Expression-Analysis


## Introduction

This project focuses on the analysis of gene expression data for various cancer types, including lung adenocarcinoma (LUAD), prostate adenocarcinoma (PRAD), breast invasive carcinoma (BRCA), kidney renal clear cell carcinoma (KIRC), and colon adenocarcinoma (COAD). The goal is to explore the gene expression patterns, identify potential biomarkers, and develop classification models to distinguish between these cancer types.

## Objectives

- Perform exploratory data analysis on the gene expression dataset
- Investigate the distribution and relationships between gene expression levels and cancer types
- Conduct dimensionality reduction techniques (PCA, LDA, t-SNE) to identify relevant features
- Apply clustering algorithms (k-means, hierarchical, mean shift) to group similar genes and samples
- Build and evaluate classification models (SVM, Random Forest, Deep Neural Network) for cancer type prediction
- Perform feature selection to identify significant genes contributing to cancer classification
- Validate the selected genes using statistical significance tests (t-test, F-test)

## Methodology

1. **Data Preprocessing and Exploratory Data Analysis**
   - Load and merge the gene expression data and cancer type labels
   - Handle missing values and perform data cleaning
   - Visualize the data using histograms, scatter plots, and heatmaps

2. **Dimensionality Reduction**
   - Apply Principal Component Analysis (PCA) to reduce the dimensionality of the gene expression data
   - Utilize Linear Discriminant Analysis (LDA) for dimensionality reduction and class separation
   - Employ t-Distributed Stochastic Neighbor Embedding (t-SNE) for visualizing high-dimensional data

3. **Clustering**
   - Perform k-means clustering on the gene expression data to identify groups of similar genes and samples
   - Apply hierarchical clustering to explore the relationships between genes and samples
   - Implement mean shift clustering to discover natural clusters in the data

4. **Classification Modeling**
   - Build multiclass classification models using Support Vector Machines (SVM), Random Forest, and Deep Neural Networks
   - Split the data into training and testing sets
   - Train and evaluate the classification models for cancer type prediction

5. **Feature Selection**
   - Apply recursive feature elimination (RFE) to select the most relevant genes for cancer classification
   - Perform statistical significance testing (t-test, F-test) to validate the selected genes

6. **Model Evaluation and Interpretation**
   - Assess the performance of the classification models using accuracy, confusion matrix, and other relevant metrics
   - Interpret the selected genes and their potential roles in cancer development and progression

## Conclusion

This project provides a comprehensive analysis of gene expression data for various cancer types. By employing dimensionality reduction techniques, clustering algorithms, and classification models, it aims to identify potential biomarkers and develop robust predictive models for cancer diagnosis and subtyping. The results can contribute to a better understanding of cancer biology and pave the way for personalized cancer treatment strategies.
