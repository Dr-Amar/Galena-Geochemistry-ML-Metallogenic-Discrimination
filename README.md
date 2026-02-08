# Big Data Mining of Galena Geochemistry using Machine Learning

![Graphical Abstract](figures/graphical_abstract.png)

This repository accompanies the manuscript:

**Big Data mining on Galena geochemistry using machine learning algorithms:  
Implications for Metallogenic Discrimination**

*Mathematical Geosciences*  
Manuscript ID: MATG-D-25-00004

---

## Overview
This study applies supervised machine learning algorithms to LA-ICP-MS trace-element
data of galena to classify metallogenic deposit types.

Deposit types include:
SEDEX, Epithermal, MVT, Metamorphosed, Skarn, Vein, and CRD.

---

## Methods
- Data preprocessing and z-score standardization
- Class-imbalance handling using SMOTE and RUC
- Machine learning models:
  - Random Forest (RF)
  - Gradient Boosting (GB)
  - Multi-Layer Perceptron (MLP)
  - Support Vector Machine (SVM)
- Blind testing and 10-fold cross-validation
- Feature importance analysis and t-SNE visualization

---

## Repository Structure
- `paper/` – Manuscript PDF
- `figures/` – Graphical abstract and plots
- `notebooks/` – Model-specific Jupyter notebooks

---

## How to Run
```bash
pip install -r requirements.txt
