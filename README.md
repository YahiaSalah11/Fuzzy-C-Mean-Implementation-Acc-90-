# Notebook Report: Fuzzy C-Means and PCA Implementation

## Objective
The goal of this notebook was to implement the Fuzzy C-Means (FCM) clustering algorithm and Principal Component Analysis (PCA) from scratch. The implementation aimed to showcase a hands-on understanding of these algorithms and their application in clustering, specifically on the well-known Iris dataset.

## Implemented Algorithms

### 1. Fuzzy C-Means (FCM)
- FCM is a soft clustering algorithm that assigns membership values to each data point for multiple clusters.
- Implemented the FCM algorithm with functions for initializing membership matrices, updating centroids, and iterating until convergence.
- Utilized NumPy for efficient array operations and simplified the code for clarity.

### 2. Principal Component Analysis (PCA)
- PCA is a dimensionality reduction technique used to transform data into a lower-dimensional space.
- Developed a PCA implementation to reduce the dimensionality of the Iris dataset for further analysis.
- Implemented the computation of eigenvalues and eigenvectors relying on external libraries(np.linalg.eig(cov)).

## Clustering Iris Dataset

**Dataset:** The Iris dataset, a classic dataset in machine learning, was used for clustering. It comprises features of iris flowers, and the goal was to group similar flowers into clusters.

**Fuzzy C-Means Clustering:**
- Implemented FCM for clustering the Iris dataset into fuzzy clusters.
- Tuned hyperparameters, such as the fuzziness coefficient (g), to achieve optimal clustering results.

**PCA Integration:**
- Applied PCA to reduce the dimensionality of the Iris dataset before clustering.
- Explored the impact of PCA on clustering accuracy and computation time.

## Results

**Without PCA:**
- Achieved an accuracy of 89% with Fuzzy C-Means clustering on the Iris dataset without PCA.

**With PCA:**
- Applied PCA for dimensionality reduction before FCM clustering.
- Achieved an accuracy of 83%, showcasing the trade-off between dimensionality reduction and clustering accuracy.

## Conclusion

This notebook demonstrated the implementation of Fuzzy C-Means clustering and Principal Component Analysis from scratch. The Iris dataset served as a practical example for evaluating the clustering performance. The results showcased the impact of dimensionality reduction through PCA on clustering accuracy, providing insights into the trade-offs involved in preprocessing steps. The overall implementation deepened the understanding of these fundamental machine learning concepts.

