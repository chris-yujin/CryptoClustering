# CryptoClustering

In this CryptoClustering we are tasked to look at a set of crypto currencies and group them into clusters based on their similarities. The features that we use to compare the separate couins are price difference at different timepoints for each coin (24 hour, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year). 

We use KMeans algorithm to be able to cluster the coins in groups based on thier similarities and differences based on the features mentioned above. Our first round of clustering we use all the features. The second time we run the KMeans we reduce the dimensions to 3 principal components. We can see that the reduced dimensions are better able to group the data and it is easier to compare on a 2 axis chart than finding out what dimesnions to use as axis on the non reduced cluster set. 
