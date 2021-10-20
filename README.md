# Cryptocurrencies
Unsupervised Machine learning

# Overview:
The following application uses an unsupervised learning approach to analyze data on cryptocurrencies traded on the market. Our goal is to create a report for an investment bank that reports cryptocurrencies investment portfolios. As we are fitting the data within a machine learning model we hope to find groupings or clusters within the data to create classifications of the cryptocurrencies investments. We are unsure of the output results, explaining the reasoning of fitting the data through unsupervised learning.

The following data was retrieved from CryptoCompare.

# Steps:
1. Preprocess the dataset
2. Use get_dummies to create variables for two text features, Algorithm and Proof Type. Then store the resulting data
3. Use StandardScaler to standardize the features from the DataFrame.
4. Apply the Principal Component Analysis (PCA) algorithm and reduce the dimensions of the dataframe
5. Use the K-means algorithm and create an elbow curve to find the best values for K from the DataFrame
6. Generate 3D Scatter plot and hvplot
7. Run the K-means algorithm to predict the K clusters for the cryptocurrencies

# Tools:
Python, Pandas, StandardScaler, K-means, Principal Component Analysis, Jupyter Notebook

# Summary:
Our DataSet

![Screenshot (128)](https://user-images.githubusercontent.com/81484054/138007994-1d428486-17b0-45cf-acc0-a8ca05e29a4d.png)

The following 3D scatter plot shows three different cryptocurrencies clusters.

![Screenshot (126)](https://user-images.githubusercontent.com/81484054/138008045-bd5a8014-10cd-4dbd-a9e7-ee34b113bbb3.png)

The following two-dimensional graph shows a relationship between the total coin supply and total coin mined.

![Screenshot (127)](https://user-images.githubusercontent.com/81484054/138007999-ee2547d0-25f5-4f8a-8927-562950247fd0.png)

# Results:

Following from the above graphs we can see there are four different cluster groups within the 3D graph. As two groups are grouped closely together this will show that the following cryptocurrencies perform similar with the exception of a few outliers. The two other clusters are clearly separated from the original two clusters. Please note that one cluster only contains on currency.

The two-dimensional graph highlights that we have two main groups scattered between the 0% and 40% of the largest currency based on the total coin supplied. We can also see there is one currency sitting at 100% as the largest currency in volume.

