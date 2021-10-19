# Cryptocurrencies
Unspervised Machine learning

# Overview:
The following application uses an unsupervised learning approach to analyze data on cryptocurrencies traded on the market. Our goal is to create a report for an investment bank that reports cryptocurrencies investment portfolios. As we are fitting the data within a machine learning model we hope to find groupings or clusters within the data to crete classifications of the cryptocurrencie investments. We are unsure of the output results, explaining the reasoning of fitting the data through unsupervised learning.

The following data was retrieved from CryptoCompare.

# Steps:
1. Preprocess the dataset
2. Use get_dummies to create variables for two text features, Algorthn and ProofType. Then store the resulting data
3. Use StandardScaler to standardize the features from the DataFrame.
4. Apply the Principal Component Analysis (PCA) algorithm and reduce the dimensions of the dataframe
5. Use the K-means algorithm and create an elbow curve to find the best valus for K from the DataFrame
6. Generate 3D Scatter plot and hvplot
7. Run the K-means algorithm to predict the K clusters for the cryptocurrencies

# Tools:
Python, Pandas, StandardScaler, 

# Summary:
The following 3D scatter plot shows three different cryptocurrencie clusters.

The following two dimensional graph shows a relationship between the total coin supply and total coin mined. 

# Results:

Following from the above graphs we can see there are four different cluster groups within the 3D graph. As two groups are grouped closley together this will show that the following cryptocurrencies perform similary with the execption of a few outliers
