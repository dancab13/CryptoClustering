# CryptoClustering
Using machine learning to find clusters in cryptocurreny data
![Crypto_Clustering_Line_Plots](https://github.com/dancab13/CryptoClustering/assets/147662348/edec596f-29b4-416c-97df-677407787fbb)
![Crypto_Clustering_Scatter_Plots](https://github.com/dancab13/CryptoClustering/assets/147662348/6192eb95-1306-4c94-b23f-c8d69856939d)

This repo contains a Jupyter Notebook file and a Resources folder with a CSV data file. The Jupyter Notebook file uses Python, Pandas, and Sci-kit Learn to use unsupervised machine learning algorithms to analyze cryptocurrency data.

Using the elbow method, I used the data to find the best number of clusters to analyze the data. I then used KMeans to make predictions about the data. To further refine the data, I used PCA and performed another elbow method and KMeans test. 

Using PCA was beneficial and preferred. After plotting each cluster of data, it was clear that using PCA better showed outliers in the data and gave tighter clusters.

All code is adapted from bootcamp class activities unless noted otherwise.

