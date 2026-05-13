# Customer Segmentation

## Overview

This project applies unsupervised machine learning techniques to discover and analyze customer segments from real-world data. By leveraging clustering algorithms, we identify distinct customer groups to enhance targeted marketing, develop tailored product strategies, and improve business decision-making. The repository demonstrates the full segmentation workflow, from exploratory data analysis to final clustering and interpretation.

## Repository Contents

- **[Group14_EDA_Notebook.ipynb](Group14_EDA_Notebook.ipynb):** Exploratory Data Analysis (EDA) notebook—cleans, visualizes, and investigates the customer dataset to inform feature selection and clustering readiness.
- **[Customer Clustering_Notebook.ipynb](Customer%20Clustering_Notebook.ipynb):** Main customer clustering pipeline: feature engineering, model fitting (e.g., k-means, hierarchical), cluster validation, and result analysis.
- **[Group14_Clustering_Report.pdf](Group14_Clustering_Report.pdf):** Formal report summarizing methodology, insights, and business implications of the discovered segments.
- **[Segmentation.py](Segmentation.py):** Python script for running core segmentation code outside of the notebook environment (e.g., for automation or integration).

## Features

- Handles missing data and categorical features with robust preprocessing.
- Visualizes customer attributes and clustering results for interpretability.
- Benchmarks multiple clustering algorithms and uses metrics like silhouette score for evaluation.
- Explains what distinguishes each customer segment in practical business terms.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

**Install essentials:**
```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

### Usage

1. **Clone the repo:**
    ```bash
    git clone https://github.com/Ozougwu/Customer_Segmentation.git
    cd Customer_Segmentation
    ```

2. **Launch Jupyter and open a notebook:**
    ```bash
    jupyter notebook Group14_EDA_Notebook.ipynb
    ```
    or
    ```bash
    jupyter notebook Customer\ Clustering_Notebook.ipynb
    ```

3. **Run cells in order** to explore the data and perform segmentation.

4. Alternatively, **run the Python script** directly:
    ```bash
    python Segmentation.py
    ```

> Make sure your dataset is available at the path specified in the notebooks or script.

## Project Goals

- Identify actionable customer segments using unsupervised learning.
- Provide reproducible analysis with clear code and visual explanations.
- Support business strategies with interpretable data-driven insights.

## Results

The analysis reveals meaningful customer groups, highlights their characteristics, and gives recommendations for targeted engagement. Detailed findings, cluster profiles, and business actions are reported in [Group14_Clustering_Report.pdf](Group14_Clustering_Report.pdf).
