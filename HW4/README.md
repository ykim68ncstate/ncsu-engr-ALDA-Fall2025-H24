# HW4: Machine Learning Models (SVM & ANN)

## Directory Structure

```
HW4/
│
├── HW4_H24.pdf                ← Assignment description
├── HW4_Q3.ipynb               ← Q3. Linear Regression (Real Estate dataset)
├── HW4_Q4.ipynb               ← Q4. Artificial Neural Network (ANN)
├── HW4_Q5.ipynb               ← Q5. Support Vector Machine (SVM)
│
├── HW4_data/                  ← All data files
│   ├── real_estate.csv        ← Dataset for Q3
│   ├── ann_2025/              ← Datasets for Q4 (ANN)
│   │   ├── train_data_2025.csv
│   │   ├── val_data_2025.csv
│   │   └── test_data_2025.csv
│   └── SVM_2025/              ← Datasets for Q5 (SVM)
│       ├── svm_2025.csv
│       ├── train_data_2025.csv
│       └── test_data_2025.csv
│
├── outputs/                   ← Output results
│   ├── svm_support_vectors_plot.png
│   └── (other generated results)
│
└── README_Q4.md               ← Additional notes for Q4
```

---

## Problem Overview

| Question | Topic | Description |
|-----------|--------|-------------|
| **Q3** | Linear Regression | Implements a multiple linear regression model using `real_estate.csv` to predict house prices. |
| **Q4** | Artificial Neural Network (ANN) | Builds and trains a multi-layer perceptron (MLP) using datasets from `ann_2025/` and evaluates model performance. |
| **Q5** | Support Vector Machine (SVM) | Applies SVM theory and kernel methods on the `SVM_2025/` dataset, identifies support vectors, and visualizes the decision boundary. |

---

## Required Packages

Make sure the following libraries are installed:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

---

## Output Files

- `outputs/svm_support_vectors_plot.png`  
  → Visualization of support vectors and decision boundaries from Q5 (SVM).

- `README_Q4.md`  
  → Describes the ANN structure, training parameters, and performance metrics for Q4.

---
