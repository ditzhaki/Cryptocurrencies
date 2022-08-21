# Cryptocurrencies

## Overview

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. Our goal is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. Using the **crypto_data.csv** file as our dataset, we performed the following steps to acheive our goal:

* With the dataset not being ideal, we had to preprocess the data by cleaning, encoding, and scaling it to better work with the algorithms.
* Using PCA (Principle Component Analysis), we were able to to reduce the dimensions of the dataframe.
* Using the K-means algorithm, we created an elbow curve plot which allowed us to find the best number of clusters for our data.
* Finally, we visualized the data by creating a 3D scatter plot and a 2D scatter plot. 

The results of our analysis can be seen in the images below. 

## Results

The Elbow Curve produced can be seen below. It allowed us to estimate a total of 4 clusters. 

<img width="715" alt="Screen Shot 2022-08-21 at 11 08 35 AM" src="https://user-images.githubusercontent.com/101564349/185797689-e990d4b9-0deb-4d65-8c61-f5eec9044575.png">

The following 3D Scatter Plot was created using the PCA data and clusters.

<img width="924" alt="Screen Shot 2022-08-21 at 11 09 06 AM" src="https://user-images.githubusercontent.com/101564349/185797716-cf5a3975-ba46-4f08-b73d-b26cb579f21e.png">

Lastly, the 2D Scatter Plot was created using the Total Coins Mined and the Total Coin Supply. 

<img width="642" alt="Screen Shot 2022-08-21 at 11 10 30 AM" src="https://user-images.githubusercontent.com/101564349/185797795-ef4be8cb-b975-4ac8-8068-df9e8f8f0fb6.png">
