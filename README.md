# CryptoClustering
# Technologies Used:
Python (programming language)
Jupyter Notebook (IDE for Python)
Pandas (data manipulation library)
Scikit-learn (machine learning library)
hvPlot (interactive plotting library)
NumPy (numerical computing library)

# Overview:
In the data preparation phase, utilize the StandardScaler() from scikit-learn to normalize the data and create a DataFrame with the scaled data, setting "coin_id" as the index. Subsequently, employ the elbow method to determine the optimal number of clusters (k) for K-Means on the original data, visualizing the results through a line chart of inertia values. I proceed to cluster cryptocurrencies using K-Means with the identified optimal k, and visualize the clusters through a scatter plot using hvPlot. Subsequently, I optimize the clusters with Principal Component Analysis (PCA) by creating a model with three principal components and evaluating the explained variance. I utilizes PCA data to repeat the elbow method, determining the best k, and cluster cryptocurrencies using K-Means with PCA data. I visualized and compared the results through composite plots.
