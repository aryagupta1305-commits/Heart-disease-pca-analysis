# Heart Disease Dimensionality Reduction with PCA

## Overview
Applies Principal Component Analysis (PCA) to the Heart Disease dataset (303 records, 13 features, 1 binary target) after standardization to evaluate variance retention and 2D component projection.

## Tech Stack
- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (`StandardScaler`, `PCA`)

## Key Metrics & Findings
- **Dataset Shape:** 303 rows x 14 columns (13 predictor features + `target`)
- **Variance Explained:** PC1 captures 21.25% variance, PC2 captures 11.82%, and the first two components together capture 33.07% cumulative variance
- **Cumulative Variance Milestones:** Reaches 51.57% with 4 components, 79.50% with 8 components, 89.81% with 10 components, and 97.14% with 12 components
- **2D Projection:** Reduced data from (303, 13) to (303, 2) and plotted class separation across PC1 and PC2

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Open `heart_disease_pca.ipynb` in Jupyter Notebook and run all cells
