# Cryptocurrencies

## Overview of the analysis:
Create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
 
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results


## Preprocessing Data
<!-- ![Pre-process]() -->
![Post-process](https://github.com/HappyM0f0/Cryptocurrencies/blob/main/images/transformation.png)
- before processing the data set has a total of 1252
- after processing the data set has a total of 532
- Removed cryptos that were never mined, or traded
- Removed rows that contained null values


## Elbow Graph
![Elbow](https://github.com/HappyM0f0/Cryptocurrencies/blob/main/images/elbow%20graph.png)
- best K is 4

## 3d Scatter
![3dScatter](https://github.com/HappyM0f0/Cryptocurrencies/blob/main/images/3d.png)
- 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components

## 2d Scatter
![2dScatter](https://github.com/HappyM0f0/Cryptocurrencies/blob/main/images/2d_scatter.png)
- TotalCoinMined vs TotalCoinSupply

## Summary
- Classification of 532 cryptocurrencies based on similarities of their features