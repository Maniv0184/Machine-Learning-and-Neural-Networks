# Machine-Learning-and-Neural-Networks
# Clustering Wine Quality Data Using K-Means and PCA

## Overview
This project explores how Principal Component Analysis (PCA) improves the performance of K-Means clustering on the WineQT dataset.

K-Means is a widely used clustering algorithm, but it struggles with high-dimensional and correlated data. PCA is applied to reduce dimensionality, remove redundancy, and improve clustering quality.

---

## Objectives
- Apply K-Means clustering to wine quality data
- Determine optimal number of clusters using Elbow and Silhouette methods
- Apply PCA for dimensionality reduction
- Compare clustering performance before and after PCA
- Interpret clusters using feature distributions

---

## Dataset
- Dataset: WineQT (Wine Quality Dataset)
- Source: Kaggle  
- Features include acidity, alcohol content, sulphates, etc.

---

## Methodology
1. Data preprocessing (cleaning, feature selection)
2. Feature scaling using StandardScaler
3. Correlation analysis
4. K-Means clustering
5. Optimal cluster selection:
   - Elbow Method
   - Silhouette Score
6. PCA transformation
7. Clustering before and after PCA
8. Cluster interpretation using boxplots and PCA loadings

---

## Results
- PCA reduced dimensionality while preserving most variance
- Improved cluster separation after PCA
- Higher silhouette score after PCA
- Clearer visualization in 2D space
- Meaningful cluster interpretation based on features

---

##  Key Visualisations
- Correlation heatmap
- Elbow method plot
- Silhouette score plot
- PCA explained variance plot
- Clustering before and after PCA
- Cluster centroids
- PCA loadings
- Boxplots for cluster interpretation

---

##  Key Insights
- PCA improves clustering performance by removing redundancy
- K-Means performs better in lower-dimensional space
- Clusters show meaningful differences in wine features

---

##  Limitations
- K-Means assumes spherical clusters
- PCA is linear and may miss non-linear patterns
- Results depend on feature selection

---

## Future Work
- Apply DBSCAN or hierarchical clustering
- Use t-SNE or UMAP for non-linear dimensionality reduction
- Test on larger datasets

---

## 📁 Repository Structure
