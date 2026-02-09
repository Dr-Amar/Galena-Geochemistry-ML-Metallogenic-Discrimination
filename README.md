# Big Data Mining of Galena Geochemistry using Machine Learning

![Graphical Abstract](./figures/graphical_abstract.png)

---

## Publication Status

This repository accompanies the peer-reviewed manuscript:

**Big Data mining on galena geochemistry using machine learning algorithms:  
Implications for metallogenic discrimination**

*Accepted for publication in* **Mathematical Geosciences**  
Manuscript ID: **MATG-D-25-00004**

The final published article is **not open access**. In accordance with publisher
copyright policies, the full manuscript text is **not shared** in this repository.
This repository provides the **supporting machine-learning workflows, figures,
and reproducible analysis** underlying the study.

---

## Overview

This study applies supervised machine-learning algorithms to **LA-ICP-MS
trace-element geochemistry of galena** in order to classify metallogenic deposit
types and evaluate their geochemical discriminability.

The compiled dataset represents a large and diverse collection of galena
analyses spanning multiple deposit environments. Machine-learning models are
used to (i) quantify classification performance, (ii) identify diagnostic trace
elements, and (iii) explore the metallogenic significance of galena chemistry in
a data-driven framework.

### Deposit types investigated

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
- Class-imbalance handling using **SMOTE** and **random undersampling with
  clustering (RUC)**
- Supervised machine-learning models:
  - Random Forest (RF)
  - Gradient Boosting (GB)
  - Multi-Layer Perceptron (MLP)
  - Support Vector Machine (SVM)
- **Blind testing** and **k-fold cross-validation**
- Model performance evaluation using accuracy and confusion matrices
- Feature-importance analysis
- **t-SNE** visualization for high-dimensional data exploration

---

## Repository Structure

Galena-Geochemistry-ML-Metallogenic-Discrimination/
│
├── figures/
│ ├── graphical_abstract.png
│ └── README.md
│
├── notebooks/
│ ├── 1_Galena-RF.ipynb
│ ├── 2_Galena-GB.ipynb
│ ├── 3_Galena-MLP.ipynb
│ └── 4_Galena-SVM.ipynb
│
├── README.md
├── DISCLAIMER.md
└── .gitignore



---

## Citation

Formal citation details (DOI, volume, issue, and page numbers) will be added once
The article is published online.

Until then, if you use this repository, please cite the corresponding journal
article as:

> Gul, M. A., *et al.* (accepted). Big Data mining on galena geochemistry using
> machine learning algorithms: Implications for metallogenic discrimination.
> **Mathematical Geosciences**.

---

## License and Disclaimer

This repository does **not** contain the final published manuscript or any
publisher-copyrighted material. All rights to the published article remain with
the publisher.

For copyright and usage information, see  
[`DISCLAIMER.md`](DISCLAIMER.md).

---

## Contact

**Dr. Amar Gul**  
Geoscientist | Machine Learning | Metallogenic Modeling  
GitHub: https://github.com/Dr-Amar
