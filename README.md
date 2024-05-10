# CryptoClustering

In this challenge, we leverage Python and unsupervised learning techniques to predict the impact of 24-hour or 7-day price changes on cryptocurrencies. The main steps involved in the analysis are as follows:

1. Find the Best Value for k Using the Original Scaled DataFrame
We employ the elbow method to identify the optimal number of clusters (k) using the original scaled DataFrame. By computing the inertia for different values of k and plotting it, we determine the best value for k.

2. Cluster Cryptocurrencies with K-means Using the Original Scaled Data
Utilizing the K-means algorithm, we cluster the cryptocurrencies based on the optimal number of clusters obtained in the previous step. This allows us to group similar cryptocurrencies together.

3. Optimize Clusters with Principal Component Analysis (PCA)
To further optimize the clusters, we perform Principal Component Analysis (PCA) on the original scaled DataFrame. By reducing the dimensionality of the data and retaining significant variance, we aim to improve the clustering results.

4. Find the Best Value for k Using the PCA Data
Similar to the first step, we apply the elbow method to the PCA-transformed data to determine the best value for k. This helps ensure that the clustering process is robust and effective.

5. Cluster Cryptocurrencies with K-means Using the PCA Data
Finally, we cluster the cryptocurrencies based on the optimal number of clusters obtained from PCA. This allows us to create more meaningful and interpretable clusters, facilitating analysis and decision-making.

Resources
StackOverflow
ChatGPT
Gemini
Previous class assignments
Google
