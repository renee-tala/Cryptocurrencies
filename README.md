# Cryptocurrencies

## Purpose of Analysis

We are completeing an analysis for Accountability Accounting, an investment bank that wants to offer a new cryptocurrency investment portfolio for its customers. We must create a report about the current cryptopcurrencies in the market. This will provide Accountability Analysis with classifications of the cryptocurrencies. Since there are no known results, we will be using Unspervised Learning. 

- Resources
  - crypto_data.csv
  - Pandas, sklearn

In four steps, we will:
  - Preprocess the data for Principal Component Analysis (PCA)
  - Reduce the data dimensions using PCA
  - Cluster the Cryptocurrencies using K-means
  - Visual the Cryptocurrencies results 

## Results
- This is what the data looks like reduced into three Principal Component Analyses:
![PCA](img/reduced_pca.png)

- Afterwards, we cluster using K-means and display the data as an Elbow Curve: 
![elbowcurve](img/elbowcurve_kmeans.png)

- Here is the table of tradable cryptocurrencies:
![clusteredtable](img/clustered_table.png)

- Here are the tradable cryptocurrencies as a 3d plot:
![3dplot](img/3d_plot.png)

- After scaling the data, we can view it as a scatterplot:
![scatterplot](img/scatterplot.png)

