# Unsupervised Learning on Causes of Death in Children Under 5

## Project Overview
This project applies unsupervised learning techniques to analyze global child mortality data from **1990 to 2019**, sourced from *Our World in Data*. The goal is to uncover patterns in causes of death among children under five and cluster countries based on similar mortality trends using techniques like **PCA, SVD, K-Means, and Hierarchical Clustering**.

---

## Objectives
- Identify key causes of death across countries and years.
- Use dimensionality reduction (PCA, SVD) to simplify high-dimensional data.
- Apply clustering algorithms to uncover country groupings with similar mortality patterns.
- Support global health policy by extracting interpretable insights.

---

## Methodology
- **Data Source**: Our World in Data – Causes of death in children under 5 (1990–2019)
- **Preprocessing**:
  - Removed missing and cumulative 'World' entries
  - Renamed lengthy columns for clarity
  - Aggregated data across years per country
- **Dimensionality Reduction**:
  - PCA and SVD used to extract 7 principal components explaining 90%+ variance
- **Clustering**:
  - **K-Means**: Optimal clusters determined via Elbow Method
  - **Hierarchical Clustering**: Dendrograms plotted with complete and centroid linkage

---

## Key Insights
- Top causes of death: **respiratory infections**, **preterm birth**, and **diarrheal diseases**
- Countries with the highest death tolls: **India**, **Nigeria**, **Pakistan**, **Ethiopia**
- PCA revealed 7 components capturing most variance
- K-Means with `k=29` and Hierarchical Clustering exposed meaningful global groupings by region and mortality pattern

---

## Visualizations
- Scree plots for PCA and SVD
- Choropleth map of total deaths by country and year
- Cluster plots from K-Means and hierarchical dendrograms
- Trends over time for top causes of death

---

## Technologies Used
- Python: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
- Machine Learning: PCA, SVD, KMeans, Agglomerative Clustering

---
