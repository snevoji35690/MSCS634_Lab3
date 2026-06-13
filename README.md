# MSCS_634_Lab_3

## Student Name
Srujana Nevoji

## Course
MSCS 634 - Data Mining

## Lab Title
K-Means and K-Medoids Clustering

## Purpose
The purpose of this lab is to apply clustering techniques using the Wine dataset from sklearn. This lab compares K-Means and K-Medoids clustering using performance metrics and visualization.

## Dataset
The Wine dataset was loaded from sklearn.datasets. It contains chemical analysis results of wines from three different classes.

## Methods Used
- Data loading and exploration
- Class distribution analysis
- Z-score standardization
- K-Means clustering with k = 3
- K-Medoids clustering with k = 3
- Silhouette Score
- Adjusted Rand Index
- PCA visualization

## Key Insights
- Standardization was important because clustering algorithms are distance-based.
- K-Means and K-Medoids both grouped the data into three clusters.
- Silhouette Score helped measure how well-defined the clusters were.
- Adjusted Rand Index helped compare clustering labels with actual class labels.
- K-Means is efficient for clean datasets.
- K-Medoids is more robust when data contains outliers.

## Challenges
One challenge was installing the K-Medoids package. Since scikit-learn-extra did not install correctly, a manual K-Medoids function was used instead. Another challenge was visualizing high-dimensional data, which was handled using PCA.

## Conclusion
This lab provided hands-on experience with unsupervised learning. K-Means and K-Medoids were compared using clustering metrics and visualizations. The results helped show how different clustering methods can produce different groupings even when using the same dataset.