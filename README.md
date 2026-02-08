# Big Data Mining of Galena Geochemistry using Machine Learning

![Graphical Abstract](figures/graphical_abstract.png)



This repository accompanies the manuscript:

**Big Data mining on Galena geochemistry using machine learning algorithms:  
Implications for Metallogenic Discrimination**

*Mathematical Geosciences*  
Manuscript ID: **MATG-D-25-00004**

---

## Overview
This study applies supervised machine learning algorithms to LA-ICP-MS trace-element
data of **galena** to classify metallogenic deposit types.

Deposit types include:
**SEDEX, Epithermal, MVT, Metamorphosed, Skarn, Vein, and CRD**.

---

## Methods
- Data preprocessing and **z-score standardization**
- Class-imbalance handling using **SMOTE** and **RUC**
- Machine learning models:
  - Random Forest (**RF**)
  - Gradient Boosting (**GB**)
  - Multi-Layer Perceptron (**MLP**)
  - Support Vector Machine (**SVM**)
- Evaluation strategy:
  - **Blind testing**
  - **10-fold cross-validation**
- Interpretation:
  - **Feature importance**
  - **t-SNE visualization**

---

## Repository Structure
```text
figures/    # graphical abstract and figures
notebooks/  # RF, GB, MLP, SVM notebooks
