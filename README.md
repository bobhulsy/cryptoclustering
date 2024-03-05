
# Cryptocurrency Clustering Project

This project involves the use of unsupervised learning techniques to analyze and cluster cryptocurrencies. The goal is to group cryptocurrencies based on their performance in different time periods and other features, which can provide insights for investment strategies.

## Steps Involved

1. **Data Preparation**: The first step involves preparing the data for analysis. This includes cleaning the data, handling missing values, and normalizing the data for machine learning algorithms.

2. **Dimensionality Reduction**: Principal Component Analysis (PCA) is used to reduce the dimensionality of the data. This involves transforming the data from its original high-dimensional space into a new space with fewer dimensions.

3. **Clustering**: K-Means clustering is used to group the cryptocurrencies based on their features. The optimal number of clusters is determined using the Elbow Method, which involves plotting the explained variance (or inertia) as a function of the number of clusters and picking the elbow of the curve as the number of clusters to use.

4. **Visualization**: The clusters are visualized using scatter plots. The plots are colored by cluster assignment, and hovering over a point displays the 'coin_id' for that point.

## Results

The results of the clustering can provide insights into the similarities and differences between different cryptocurrencies. This can be useful for understanding the dynamics of the cryptocurrency market and informing investment decisions.
