# Clustering Analysis Project

This project explores and compares different clustering methods applied to a dataset where the true class labels of each sample are known. The main objective is to evaluate the performance of clustering algorithms in grouping similar data points without prior knowledge of their categories. We implement three key clustering techniques—K-means, hierarchical clustering (using single and complete linkage), and assess their effectiveness using metrics such as silhouette score, adjusted Rand index, and homogeneity/completeness/V-measure.

## Project Structure

- **Data Preparation**: Includes preprocessing and scaling of the dataset to optimize clustering results.
- **Clustering Models**:
  - **K-means**: Applied with the optimal number of clusters, determined through silhouette analysis.
  - **Hierarchical Clustering**: Implemented with single and complete linkage methods, and visualized using dendrograms.
- **Evaluation and Comparison**:
  - Metrics computed include silhouette score, adjusted Rand index, homogeneity, completeness, and V-measure.
  - Comparison between K-means and hierarchical clustering to examine the consistency of clustering results.

## Getting Started

To run this project:
1. Install the required libraries.
2. Run the notebook or script to preprocess the data, apply clustering algorithms, and analyze the results.

## Results

The project provides insights into:
- The effectiveness of different clustering techniques on this dataset.
- How clustering evaluation metrics can guide the selection of a suitable clustering model.
  
This project demonstrates how clustering methods can offer meaningful groupings in unsupervised learning scenarios, especially when evaluating without prior class labels.

---

Feel free to clone this repository, experiment with different parameters, and expand upon the clustering methods used!

