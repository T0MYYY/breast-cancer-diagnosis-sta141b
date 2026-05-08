# Breast Cancer Diagnosis Analysis — UC Davis STA 141B Final Project

A data science project analyzing the **Breast Cancer Wisconsin dataset** to classify tumors as malignant or benign using exploratory data analysis, dimensionality reduction, and multiple machine learning models.

**Course:** STA 141B — Data & Web Technologies (Winter 2022, UC Davis)  
**Team:** Group 14 — Chiyang Chen, Purui Niu, Shuying Li, Yinyin Guan, Yixuan Li

---

## Project Overview

| Stage | Description |
|---|---|
| Data Collection | Download Breast Cancer Wisconsin dataset + web scraping |
| Data Cleaning | Handle missing values, remove irrelevant features |
| EDA | Visualize feature distributions and class separability |
| Feature Engineering | Standardization, correlation analysis |
| Dimensionality Reduction | PCA to identify principal components |
| Modeling | Logistic Regression, KNN, K-Means, SVM, ANN |

---

## Dataset

**Breast Cancer Wisconsin (Diagnostic)**
- 569 samples, 30 numeric features computed from digitized images of fine needle aspirate (FNA) of breast masses
- Target: `diagnosis` — Malignant (M) or Benign (B)
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

---

## Files

| File | Description |
|---|---|
| `notebook.ipynb` | Main Jupyter Notebook with full analysis code |
| `notebook_rendered.html` | Rendered HTML with all outputs and visualizations |
| `report.pdf` | Final written report |

---

## Key Methods

- **PCA** — reduce 30 features to principal components, visualize class clustering
- **Logistic Regression** — linear baseline classifier
- **K-Nearest Neighbors (KNN)** — distance-based classifier
- **K-Means Clustering** — unsupervised grouping
- **Support Vector Machine (SVM)** — margin-maximizing classifier
- **Artificial Neural Network (ANN)** — multi-layer perceptron

---

## Libraries

```
pandas · numpy · matplotlib · seaborn · scikit-learn · pywaffle · missingno
```

---

## How to Run

```bash
# 1. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn pywaffle missingno tqdm

# 2. Open notebook
jupyter notebook notebook.ipynb
```

The notebook will automatically download the dataset from Google Drive on first run.  
Alternatively, open `notebook_rendered.html` in a browser to view all outputs without running any code.

---

## Results

See `report.pdf` for full analysis results and model performance comparison.
