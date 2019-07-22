# Unsupervised Single‑Cell Analysis in Triple‑Negative Breast Cancer

## Broad Problem Statement
Triple-negative breast cancer is an aggressive type of cancer that is poorly understood both in
terms of its chemistry and its treatment. Some years ago, women with triple-negative breast
cancer who also had diabetes and were taking an anti-diabetic drug, metformin, saw their
tumors shrinking. Why their tumors shrank was unclear. In this project, we’re going to
investigate how metformin impacts genes that might be responsible for the spreading of
triple-negative breast cancer.
You’ll be exploring various new data science methods in solving this problem and are
free to use Python packages unless otherwise specified (see Useful Python libraries and
APIs section for help).

## Learning Objectives
Concepts you will learn and apply
● Data pre-processing and visualization
● Bayesian Networks
● Statistical analysis (Kolmogorov–Smirnov test, Multiple testing, Q-Q plot)
● Dimensionality reduction (Principal Component Analysis, t-SNE)
● Clustering (K-Means, Gaussian Mixture Model clustering, Hierarchical clustering)

## Dataset Description

The biologists have obtained approximately 400 triple-negative breast cancer cells, half of which
are treated with metformin (referred to as metformin-treated cells) and half that are not (referred
to as baseline cells).The cells were sequenced using scRNA-seq, and the resulting data reflect
~20,000 genes and their associated gene expressions for baseline and metformin-treated cells.

**GeneExpression_Baseline.csv**: Gene expression matrix for baseline cells

**GeneExpression_Metformin.csv**: Gene expression matrix for metformin-treated cells, similar to GeneExpression_Baseline.csv.

**QualityControl.csv**: Experiment conditions and corresponding quality records collected from previous scRNA-seq experiments.

**BayesInferenceBase.csv**: Experiment conditions collected for baseline cells in GeneExpression_Baseline.csv

**BayesInferenceMetf.csv**: Experiment conditions collected for baseline cells in GeneExpression_Metformin.csv, similar to BayesInferenceBase.csv

**PathwayDictionary.txt**

## Tasks Description
**Note:** Detailed tasks requirements can be found in project description document. 
### Task 1: Data Cleaning and Visual Inspection
1. Bayesian Network for Quality Control
2. Data Standardization
3. Visual Inspection

### Task 2: Statistical Analysis
1. Kolmogorov–Smirnov (KS) Test
2. Multiple Testing

### Task 3: Dimensionality Reduction and Clustering
1. Principal Component Analysis (PCA)
2. t-Distributed Stochastic Neighbor Embedding (t-SNE)
3. Clustering

### Task 4: Interpret Results
1. Identify altered genes
2. Gene set characterization
