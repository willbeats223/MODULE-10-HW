# Cryptocurrency Market Data Analysis

This project is focused on analyzing cryptocurrency market data by applying machine learning techniques like KMeans clustering and Principal Component Analysis (PCA). We start by loading the data, visualizing it, and then scaling it for the machine learning processes. The Elbow Curve is used to determine the optimal number of clusters for our KMeans algorithm. Afterwards, we perform dimensionality reduction using PCA and visualize the results.

## Dependencies
The following python libraries are necessary for this project:

- pandas
- hvplot
- pathlib
- sklearn (modules: cluster, decomposition, preprocessing)


## Project Structure
- Load the market data from a CSV file into a pandas DataFrame.
- Visualize the data using hvplot for better understanding.
- Normalize the data using sklearn's StandardScaler to prepare for machine learning algorithms.
- Run KMeans clustering algorithm, testing for different number of clusters to find the optimal number using the Elbow Curve.
- Predict the clusters for the data.
- Implement Principal Component Analysis (PCA) for dimensionality reduction.
- Perform KMeans clustering on the transformed PCA data.
- Plot and visualize the results of the KMeans and PCA process.


## Datasets
`crypto_market_data.csv` 



## Author
This project is created by William Stanton.


