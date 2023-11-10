# CryptoClustering
## References
I used the solution for homework exercise 19.3 - 04-Stu_Energize_Your_Stock_Clustering as a reference while completing this CryptoClustering challenge. 

## Code 

### 1. Setting it up

* First the appropriate libraries and dependencies are imported and a DataFrame is created for teh crypto_market_data.csv.

### 2. Prepare the Data

* The data is scaled using StandardScaler to adjust all of the numerical data, then the scaled data is put into a new dataframe. 

### 3. Find the Best Value for k Using the Original Data

* Using k values and inertia values an Elbow Curve is created to find the optimal number of clusters, which turned out to be 4 in this case. 

### 4. Cluster Cryptocurrencies with K-means Using the Original Data

* Using the K-Means model and n-clusters of 4 a scatter plot is created showing the different groups of crypto currencies. 

### 5. Optimize Clusters with Principal Component Analysis

* A Principal Component Analysis (PCA) is completed with n_components=3. The data is put into a graph and the explaine variance ratio is calculated for each row with a total explained variance of 0.90

### 6. Find the Best Value for k Using hte PCA Data 

* Using the PCA data another, k values and inertia values are created and an Elbow Curve is created. 

### 7. Cluster Cryptocurrencies with K-means Using the PCA Data

* Using K-Means clusters are created and the data is graphed onto a scatter plot. 

### 8. Visualize and Compare the Results

* Using hvPlot and the plus (+) operator graphs the two elbow line graphs are displayed side by side and the two scatter plots are displayed side by side for comparison



