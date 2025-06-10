# Iris Clustering with K-Means and GMM

This project applies unsupervised learning techniques—**K-Means** and **Gaussian Mixture Models (GMM)** to the classic **Iris dataset**. It includes clustering, dimensionality reduction for visualization, and evaluation using multiple performance metrics.

## K-Means vs GMM

| Aspect               | K-Means                        | GMM                                |
|----------------------|--------------------------------|-------------------------------------|
| Cluster Type         | Hard assignments               | Soft probabilistic assignments      |
| Assumes Shape        | Spherical (equal variance)     | Elliptical (varying covariance)     |
| Handles Overlap?     | Poorly                         | Better due to soft assignments      |
| Computation Speed    | Faster                         | Slower, especially with high dims   |
| Interpretation       | Simple                         | More flexible, but less intuitive   |


## Dataset
- **Source**: [UCI Machine Learning Repository – Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Loaded using**: [`ucirepo`](https://archive.ics.uci.edu/)
## Requirements
The following Python libraries are required to run the project:
~~

pip install ucirepo scikit-learn numpy matplotlib

~~

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


## Summary: K-Means vs GMM Based on Results
In this project, both K-Means and Gaussian Mixture Models (GMM) were applied to the Iris dataset. The results show that:

- **GMM** achieved significantly higher performance in terms of Adjusted Rand Index (0.90) and Homogeneity Score (0.89), indicating it more accurately grouped data points according to the true species.

- **K-Means** performed slightly better in Silhouette Score (0.55), meaning its clusters were more compact and well-separated internally.



