# CryptoClustering
Challenge#19 HW

Instructions
Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.

Load the crypto_market_data.csv into a DataFrame.

Get the summary statistics and plot the data to see what the data looks like before proceeding.

1. Prepare the Data
- Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
- Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame. Display as follows:

<img width="998" alt="1scaled_DataFrame" src="https://github.com/apkaur32/CryptoClustering/assets/150749167/f5ba54d7-db3e-4ba5-9898-3d42de34a8ee">

2. Find the Best Value for k Using the Original Scaled DataFrame

3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data.

4.  Optimize Clusters with Principal Component Analysis
- Create a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame. Display as follows:

<img width="303" alt="2PCA_DataFrame" src="https://github.com/apkaur32/CryptoClustering/assets/150749167/6ab5f896-776c-4a66-aa0b-2f48c7e45fd7">

5.  Find the Best Value for k Using the PCA Data

6.  Cluster Cryptocurrencies with K-means Using the PCA Data
    Answer the following question: What is the impact of using fewer features to cluster the data using K-Means?

7. Visualize and Compare the Results

![3_elbow_curve](https://github.com/apkaur32/CryptoClustering/assets/150749167/d7d3c2f5-b585-44fe-92d8-e4ce0990309e)

![4_scatter](https://github.com/apkaur32/CryptoClustering/assets/150749167/dbb86100-01bd-4428-9487-74bd608672e0)



Supplemental resources: 
https://www.codecademy.com/learn/dspath-unsupervised/modules/dspath-clustering/cheatsheet
This task was completed addtionally using class exercises and the help of tutor. 
