# Cryptocurrencies

# Overview

The purpose of this project was to utilize unsupervised machine learning to evaluate a cryptocurrency database and provide a report that categorizes traded cryptocurrencies into groups based on their characteristics. First, I preprocess the data and utilize principal component analysis to reduce data dimension. Then, I utilize K-Means with the aid of elbow method in order to cluster the cryptocurrencies. Finally, I visualize the classification results in 2D and 3D scatter plots.

# Results

After preprocessing the data, there is a total of 533 cryptocurrencies. I use standard scaler on the data and use three principal component on the existing data.
The elbow curve shows that aggregating by 4 clusters is the best approach.

![image](https://user-images.githubusercontent.com/95439555/180276243-35f71160-5ce2-414e-98ab-32f3a71e5df2.png)

A 3d scatter plot was deployed in order to display the PCA and the clusters.

![image](https://user-images.githubusercontent.com/95439555/180276381-c84032cf-5b58-4f7b-a1f1-af6efbbed1e7.png)

As it can be seen by the 2D graph, clustering by two features does not effectively separate the classes. However, The 3D plot was able to distinguish these clusters properly.

![image](https://user-images.githubusercontent.com/95439555/180276512-01c1c981-d65a-467a-8449-c07c4d551023.png)


