# cryptoClustering

The ipynb file within this repo contains python code that leverages unspervised learning techniques to cluster cyrptocurrencies based on 7-day and 24hr price changes. The file first scales the data using scikit-learn's standardScaler method, then determines the optimal number of clusters by leveraging the elbow method. After the optimal number of clusters has been determined, the file then clusters the data using scikit-learn's Kmeans package. The file then appends the clusters to a copy of the original dataframe and uses hvplot.pandas to visualize the results.

After establishing the clustering via the Kmeans method, the file then follows a similar process using PCA in place of KMeans. Finally, the file generates a composite plot that enables comparison of the different model outputs.
