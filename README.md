# K-Means-Clustering

The way kmeans algorithm works is as follows:

      --> Specify number of clusters K by Elbow Method.  
  
      --> Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
  
      --> Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.
   
      --> Compute the sum of the squared distance between data points and all centroids.
  
      --> Assign each data point to the closest cluster (centroid).
  
      --> Compute the centroids for the clusters by taking the average of the all data points that belong to each cluster.
  
  
  # NOTE
  
      To avoid random Initialization trap we are using K-Means++.
