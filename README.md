# Cryptocurrencies
Unsupervised Machine Learning of Crytocurrency data with Scikit-learn preprocessing and KMeans clustering.
Challenge
Provided a csv file with cryptocurrencies and information such as algorithm(s) used, trading status, total coins mined, and total coin supply; use unsupervised machine learning to group the cryptocurrencies into classifications.
Execution
Preprocessing:
1. Used pandas to reduce dataset of 1,252 cryptocurrencies to 532 that could be used for machine learning.
2. Filtered dataset by removing all currencies that are not trading, removing all currencies with no mined coins, and any records with null values.
3. Made necessary transformations to prepare remaining data into scaled data.
Clustering Cryptocurrencies using K-Means.
1. Used SKLearn Kmeans to produce an elbow curve that shows the value of '4' will serve best as the K value in the KMeans model.
2. Created and ran the KMeans function on the scaled and transformed data to generate a class of five clusters.
3. Created a combined dataset of the original filtered data with the scaled data and the cluster class values for visualization purposes.
Visualizations
1. A scatter plot using matplotlib presenting total coins mined and total coins supplied.
Conclusions
1. Bitcoin is in a class by itself. This is useful as Bitcoin can be studied as the elite cyptocurrency.
2. It would be beneficial analysis again without the Bitcoin data, so see if the elbow curve finds a different optimal cluster value and so that we can see the distribution of the data better. Essentially there are two classes, Bitcoin and all others.
3. We can use these findings to compare all cryptocurrencies against Bitcoin, and to re-run the unsupervised machine learning without Bitcoin to more fully understand the rest of the cryptocurrency market.
?



