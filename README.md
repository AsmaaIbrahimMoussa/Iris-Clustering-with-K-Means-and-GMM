# Iris Clustering with K-Means and GMM

This project applies unsupervised learning techniques—**K-Means** and **Gaussian Mixture Models (GMM)** to the classic **Iris dataset**. It includes clustering, dimensionality reduction for visualization, and evaluation using multiple performance metrics.

## 📚 Dataset
- **Source**: [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Loaded using**: [`ucirepo`](https://archive.ics.uci.edu/)

## Algorithms Used
- **K-Means Clustering** (Hard assignment)
- **Gaussian Mixture Model (GMM)** (Soft assignment)
- **PCA** for dimensionality reduction

## Evaluation Metrics
Each clustering method is evaluated using:
- **Adjusted Rand Index (ARI)**
- **Silhouette Score**
- **Homogeneity Score**

These metrics measure clustering quality against the true species labels and internal cluster structure.

## K-Means vs GMM: A Quick Comparison

| Aspect               | K-Means                        | GMM                                |
|----------------------|--------------------------------|-------------------------------------|
| Cluster Type         | Hard assignments               | Soft probabilistic assignments      |
| Assumes Shape        | Spherical (equal variance)     | Elliptical (varying covariance)     |
| Handles Overlap?     | Poorly                         | Better due to soft assignments      |
| Computation Speed    | Faster                         | Slower, especially with high dims   |
| Interpretation       | Simple                         | More flexible, but less intuitive   |




