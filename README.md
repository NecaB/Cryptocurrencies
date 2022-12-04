# Cryptocurrencies

Overview 

The purpose of this challenge was to conduct an analysis of cryptocurrency trading in the market to advise potential clients.  To conduct this analysis, we will preprocess data for unsupervised machine learning, perform PCA analysis, predict the cluster classifications and then plot the results for visualization purposes. To reduce overfitting of the data in the model we will utilize Principal Component Analysis (PCA). The main objective is to observe cryptocurrencies on the market and determined how they could be placed in a classification system for new investment portfolio for customers. 

Preprocessing the data

To guarantee best performance of the unsupervised learning model it is best practice to preprocess the data. This entails cleaning or formatting the data i.e. addressing items such as duplicates, null values, missing values and standardization of the data. 

Perform PCA analysis

Reducing the data dimensions using PCA

The machine learning identifies the principal components in the dataset so even if the dataset is reduced it will still maintain the original structure and value of being representative of the data but with lower dimensions. 

Clustering cryptocurrencies using 'K-means' 

‘K- means’ is the major determinant for the number of clusters needed to classify the data. This is done by using the average or center of the data and is displayed by plotting an Elbow Curve. Thereafter, the clusters of cryptocurrencies are created by grouping based on similarities in the data points to identify underlying patterns in the dataset. 

Visualizing cryptocurrency

The clusters are created based on a group of points that have the same patterns. The scatter plot and 3D scatterplot will be used to display the findings about cryptocurrencies. 

Results 

Below is the elbow chart created to identify the best value for K-mean from the dataframe created. This was used to determine the number of clusters that should be created. Based on the chart 4 clusters would be ideal.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/205473288-bb479c6e-ff1f-4bc8-9d56-a0fcea64fc57.png">


The data was combined and then displayed in a 3D-scatter plot with the four different clusters and PCA data. 

 <img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/205473294-bad7f69e-3e41-4b09-ac3b-10408c7d470d.png">

The hvplot.scatter reflecting Total Coin Mined on the ‘y’ axis and Total Coin Supply on the ‘x’ axis

<img width="468" alt="image" src="https://user-images.githubusercontent.com/109915684/205473326-2d0584cb-e120-4c55-85cb-fd5c29d8ca22.png">

