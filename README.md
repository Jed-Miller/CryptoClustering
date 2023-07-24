# CryptoClustering

## Background

Using an unsupervised learning techniques (K-means clustering) and PCA (Principal Component Analysis), predict whether crytpocurrencies are affected by 24 hour or 7 day price changes. 


## Instructions

1. Load and Prepare the Data
2. Find the Best Value for k Using the Original Scaled DataFrame
3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
4. Optimize Clusters with Principal Component Analysis
5. Find the Best Value for k Using the PCA Data
6. Cluster Cryptocurrencies with K-means Using the PCA Data

## Visual Analysis Charts

### Elbow Curves (Original data and PCA)

![elbow_curve](/Resources/Kmeans_elbow.png)
![PCA_elbow](/Resources/PCA_elbow.png)
<br>

### Scatterplots (Original data and PCA)

![Kmeans_scatter](/Resources/Kmeans_scatter.png)
![PCA_scatter](/Resources/PCA_scatter.png)
<br>

## Conclusion

#### After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  The biggest takeaway from the cluster analysis is that using fewer features doesn't compromise your ability to see the distinct clusters. In fact, the fewer features results in tighter clusters for the two main clusters while the cluaters of 1 have been pulled further away from the other clusters.

