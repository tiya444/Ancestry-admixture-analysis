# Computational Biology Portfolio

A collection of computational biology projects developed using Python and R, covering population genetics, genetic drift, single-cell RNA sequencing, and quantitative modelling.

## Projects

### 1. Ancestry and Admixture Analysis

**Python · NumPy · pandas · Matplotlib · Population Genetics**

Investigates whether allele-frequency variation in an admixed population can be approximated as a mixture of CEU and YRI reference populations.

The analysis estimates the CEU contribution using a sum-of-squared-errors approach and compares observed and predicted allele frequencies.

**Key result:** The best-fitting model estimated approximately 78% CEU and 22% YRI ancestry.

[View notebook](./ancestry-admixture-analysis.ipynb)

---

### 2. Wright-Fisher Genetic Drift Simulation

**Python · NumPy · Matplotlib · Stochastic Simulation · Population Genetics**

Simulates genetic drift in a finite diploid population using the Wright-Fisher model.

The project explores allele-frequency trajectories, fixation and loss, and the probability of fixation under different starting frequencies.

[View notebook](./Wright-Fisher_Genetic_Drift_Simulation.ipynb)

---

### 3. Single-Cell RNA-seq Analysis of PBMCs

**R · Seurat · PCA · UMAP · t-SNE · Louvain Clustering**

Applies a single-cell RNA-seq analysis workflow to PBMC data, including preprocessing, dimensionality reduction, graph-based clustering and marker-gene analysis.

The project investigates how clustering resolution affects the identification of cellular subpopulations.

[View notebook](./Single-Cell%20RNA-seq%20Analysis%20of%20PBMCs.ipynb)

---

### 4. RNA Polymerase II Elongation Rate Analysis

**R · ggplot2 · Regression · Quantitative Biology**

Investigates the relationship between Pol II density and transcriptional elongation rate using MCF7 gene-expression data.

Linear and logarithmic regression models are compared, and the empirical relationship is incorporated into a quantitative model of RNA production.

[View notebook](./pol_II_elongation_analysis.ipynb)

---

## Skills Demonstrated

- Python
- R
- NumPy
- pandas
- Matplotlib
- ggplot2
- Seurat
- PCA
- UMAP
- t-SNE
- Graph-based clustering
- Population genetics
- Stochastic simulation
- Statistical modelling
- Data visualisation
- Quantitative biology

## Academic Context

These projects were completed as part of Computational Biology coursework at Cornell University.

They are presented here as examples of my computational biology skills, including data analysis, programming, statistical modelling and biological interpretation.

## Data Availability

Some datasets used in these practicals were provided as part of Cornell University course materials and are therefore not included in this public repository.
