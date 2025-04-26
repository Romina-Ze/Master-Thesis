# Master-Thesis

## Project Overview

Aging affects every organ in the body — including the brain. However, the contribution of non-CNS organs to brain aging and neurodegenerative disease is poorly understood.

This thesis investigates **organ-specific biological aging** and its association with neurodegenerative diseases, using:

- Plasma proteomics (Olink platform)
- Brain imaging & organ specific phenotypes
- Statistical and machine learning models (PCA, PLS, LASSO)

The goal is to uncover **systemic biomarkers and aging patterns** that may contribute to or predict neurodegeneration.

##  Dataset

- **Source**: UK Biobank
- **Size**: 52,000+ participants
- **Processing**: Filtering, normalization, z-score outlier removal, PC1 residualization

##  Methods

- **Data Preprocessing**: MinMax normalization, PC1 removal, z-score filtering
- **PLS Regression**: Linking protein profiles with organ features
- **Statistical Testing**: t-tests between aging markers and ICD10-coded diagnoses

- Python (v3.12)
- Jupyter Notebook
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, Statsmodels
