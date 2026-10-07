# 🚀 Data-Driven E-Commerce RFM Segmentation & Predictive Clustering Pipeline

[![GitHub Stars](https://shields.io)](https://github.com)
[![Python Version](https://shields.io)](https://python.org)
[![PowerBI](https://shields.io)](https://microsoft.com)

> 💡 **Business Core:** How do we transform millions of raw transactional data rows into precision marketing strategies? This project builds a hybrid analytics pipeline using **Power BI** for ETL data preparation and **Python (Scikit-Learn)** for automated customer segmentation via Unsupervised Machine Learning.

---

## 📊 Project Showcase

### 🔍 Interactive Dashboard & Distribution Analysis
Here is the visual representation of our customer segments based on their purchase behaviors. The multi-dimensional analysis isolates low-value risk groups from high-contributing champions.

![RFM Pairplot](./RFM_Pairplot.png)

---

## 🎯 Key Business Highlights

- **Dynamic ETL Data Cleansing (Power BI)**: Processed raw transaction logs (`SalesRecordV05`), implemented conditional mapping to factor in sales volume (`Unitsold`), price parameters, and custom discount deductions (`Discount`).
- **Statistical Percentile Scoring**: Engineered robust Recency, Frequency, and Monetary scores using Pandas quantiles to avoid duplicate boundary errors (`rank(method='first')`).
- **Unsupervised Machine Learning**: Applied **Min-Max Feature Scaling** followed by **K-Means Clustering (K=4)** to separate data points into high-cohesion buyer persona networks.
- **Actionable Customer Classification**: Automatically categorized all active buyers into explicit operational segments: `High`, `Medium`, `Low`, and `Missing`.

---

## 🛠️ Tech Stack & Architecture

