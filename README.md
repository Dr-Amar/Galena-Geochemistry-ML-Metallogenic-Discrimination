# Big Data Mining of Galena Geochemistry using Machine Learning

![Graphical Abstract](./figures/graphical_abstract.png)

---

## Publication Status

This repository accompanies the peer-reviewed journal article:

**Big Data mining on galena geochemistry using machine learning algorithms:  
Implications for metallogenic discrimination**

*Accepted for publication in* **Mathematical Geosciences**  
Manuscript ID: **MATG-D-25-00004**

The final published article is **not open access**. In accordance with publisher
copyright policies, the full manuscript text is **not distributed** through this
repository. Instead, this repository provides the **supporting machine-learning
workflows, figures, and reproducible analyses** underlying the study.

---

## Overview

This study applies supervised machine-learning techniques to **LA-ICP-MS
trace-element geochemistry of galena** in order to classify metallogenic deposit
types and evaluate their geochemical discriminability.

A large and diverse global dataset of galena compositions is compiled and analyzed
using multiple machine-learning algorithms. The objectives of this work are to:

- Quantify classification performance across deposit types  
- Identify diagnostic trace elements controlling metallogenic signatures  
- Explore galena geochemistry within a robust, data-driven metallogenic framework  

---

## Metallogenic Deposit Types Investigated

- SEDEX  
- Epithermal  
- MVT (Mississippi Valley–Type)  
- Metamorphosed  
- Skarn  
- Vein  
- CRD (Carbonate-Replacement Deposits)

---

## Methods

The analytical and modeling workflow implemented in this repository includes:

- Data preprocessing and **z-score standardization**
- Class-imbalance handling using:
  - **SMOTE (Synthetic Minority Over-sampling Technique)**
  - **Random undersampling with clustering (RUC)**
- Supervised machine-learning models:
  - Random Forest (RF)
  - Gradient Boosting (GB)
  - Multi-Layer Perceptron (MLP)
  - Support Vector Machine (SVM)
- **Blind testing** and **k-fold cross-validation**
- Model performance evaluation using accuracy metrics and confusion matrices
- Feature-importance analysis
- **t-SNE** visualization for high-dimensional data exploration

---

## Repository Structure

```
Galena-Geochemistry-ML-Metallogenic-Discrimination/
├── figures/
│   ├── graphical_abstract.png
│   └── README.md
│
├── notebooks/
│   ├── 1_Galena-RF.ipynb
│   ├── 2_Galena-GB.ipynb
│   ├── 3_Galena-MLP.ipynb
│   └── 4_Galena-SVM.ipynb
│
├── README.md
├── DISCLAIMER.md
└── .gitignore
```



---

## Reproducibility

All Jupyter notebooks provided in the `notebooks/` directory are designed to be
**fully reproducible**, subject to data availability and computational environment.
Each notebook corresponds to a specific machine-learning model described in the
manuscript.

---

## Citation

Formal citation details (DOI, volume, issue, and page numbers) will be added once
the article is published online.

Until then, if you use this repository, please cite the corresponding journal
article as:

> Gul, M. A., *et al.* (accepted). Big Data mining on galena geochemistry using
> machine learning algorithms: Implications for metallogenic discrimination.
> **Mathematical Geosciences**.

---

## License and Disclaimer

This repository does **not** contain the final published manuscript or any
publisher-copyrighted content. All rights to the published article remain with the
publisher.

The code, figures, and workflows provided here are intended for **academic and
research use** only. No warranty is provided regarding suitability for commercial
or exploration decision-making.

For detailed copyright and usage information, see  
[`DISCLAIMER.md`](DISCLAIMER.md).

---

## Contact

**Dr. Amar Gul**  
Geoscientist | Machine Learning | Metallogenic Modeling  

GitHub: https://github.com/Dr-Amar

GitHub: https://github.com/Dr-Amar
