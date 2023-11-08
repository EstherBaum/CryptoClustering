# CryptoClustering
## References
I used the solution for homework exercise 19.3 - 04-Stu_Energize_Your_Stock_Clustering as a reference while completing this CryptoClustering challenge. 

FOR EVERYTING EXCEPT FOR "VISUALIZE AND COMPARE THE RESULTS"

## Code 

1. First the appropriate libraries and dependencies are imported and a DataFrame is created for teh crypto_market_data.csv.

2. The data is scaled using StandardScaler to adjust all of the numerical data, then the scaled data is put into a new dataframe. 

3. Using k values and inertia values an Elbow Curve is created to find the optimal number of clusters, which turned out to be 4 in this case. 

4. Using the K-Means model and n-clusters of 4 a scatter plot is created showing the different groups of crypto currencies. 

5. 
