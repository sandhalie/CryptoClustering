# CryptoClustering

## Overview
The primary objective of the Crypto Clustering project is to employ unsupervised learning methods, particularly K-means clustering, to forecast the influence of 24-hour or 7-day price fluctuations on cryptocurrencies. Furthermore, the project investigates the consequences of dimensionality reduction via Principal Component Analysis (PCA) on the clustering process.

## Steps

1. Load and preprocess the data.
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.

## Files
Crypto_Clustering.ipynb file contains teh code and the graphs
Resource folder contains a csv file that includes all the analysed data