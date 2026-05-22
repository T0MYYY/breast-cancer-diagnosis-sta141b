# Breast Cancer Diagnosis Analysis — UC Davis STA 141B Final Project

<!-- BADGES_BEGIN -->
<p align="center">
  <img alt="Course" src="https://img.shields.io/badge/Course-STA%20141B-022851?style=flat-square&labelColor=2a323d">
  <img alt="UC Davis" src="https://img.shields.io/badge/UC%20Davis-Data%20%26%20Web%20Tech-FFBF00?style=flat-square&labelColor=2a323d">
  <img alt="Term" src="https://img.shields.io/badge/Term-Winter%202022-2a323d?style=flat-square&labelColor=2a323d">
  <img alt="Team" src="https://img.shields.io/badge/Team-Group%20of%205-1f7a3d?style=flat-square&labelColor=2a323d">
  <img alt="Status" src="https://img.shields.io/badge/Status-Final-ec5800?style=flat-square&labelColor=2a323d">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.8-3776AB?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&labelColor=2a323d&logo=jupyter&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.0-F7931E?style=flat-square&labelColor=2a323d&logo=scikitlearn&logoColor=white">
  <img alt="pandas" src="https://img.shields.io/badge/pandas-1.4-150458?style=flat-square&labelColor=2a323d&logo=pandas&logoColor=white">
  <img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-3.5-11557C?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="seaborn" src="https://img.shields.io/badge/seaborn-0.11-4C72B0?style=flat-square&labelColor=2a323d">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.22-013243?style=flat-square&labelColor=2a323d&logo=numpy&logoColor=white">
</p>
<!-- BADGES_END -->

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
