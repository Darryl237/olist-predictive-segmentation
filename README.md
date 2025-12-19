# Olist – Predictive Analysis & Customer Segmentation

## Project Overview

This project focuses on analyzing customer behavior on the Olist e-commerce platform using a complete data science pipeline.  
The objective is to transform raw transactional data into actionable business insights through customer segmentation and predictive analysis.

The project is designed following professional data science standards, ensuring clarity, reproducibility, and business relevance.

---

## Objectives

- Analyze customer purchasing behavior in an e-commerce context
- Build meaningful and interpretable customer segments
- Link customer segments to key business variables
- Support marketing and strategic decision-making
- Provide a reusable analytical framework for future extensions

---

## Dataset

**Brazilian E-Commerce Public Dataset by Olist**
Public dataset containing anonymized information about:

- Customers
- Orders
- Products
- Payments
- Reviews

Source: Kaggle (Olist Dataset)

---

## Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Git / GitHub

---

## Project Structure

The project is organized as follows:

olist-predictive-segmentation/
│
├── data/
│ ├── raw/ # Raw datasets (not included in the repository)
│ ├── interim/ # Cleaned and intermediate datasets (parquet files)
│ └── processed/ # Final datasets (optional)
|
│models/
├── rf_cluster_classifier.joblib
├── scaler_cluster.joblib
└── cluster_features.json
|
├── notebooks/
│ ├── 00_setup.ipynb
│ ├── 01_data_audit_schema.ipynb
│ ├── 02_cleaning_eda.ipynb
│ ├── 03_feature_engineering_clients.ipynb
│ ├── 04_segmentation_preparation.ipynb
│ ├── 05_business_analysis.ipynb
│ └── 06_predictive_modeling.ipynb
│
├── reports/ # Figures, visualizations, and summaries
├── src/ # Reusable Python scripts
│
├── .gitignore
├── .env.example
├── requirements.txt
└── README.md

## Authors

- Darryl Momo
- Demanou Levana
- Laeticia Joyce Chuiedjui
