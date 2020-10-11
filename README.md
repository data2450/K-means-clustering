# K-means-clustering on mall_customer.csv

dataset from kaggle
# what is K means clustering

K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. The results of the K-means clustering algorithm are:

The centroids of the K clusters, which can be used to label new data Labels for the training data (each data point is assigned to a single cluster)

# application

The K-means clustering algorithm is used to find groups which have not been explicitly labeled in the data. This can be used to confirm business assumptions about what types of groups exist or to identify unknown groups in complex data sets. Once the algorithm has been run and the groups are defined, any new data can be easily assigned to the correct group.

use cases:coustmer segmentation based on their purchase behavior,Group inventory by sales activity,grouping images etc.

# working

Initialisation:Pick the n.o of clusters K you want to find .K random points to serve as an initial guess for the cluster centers.

1)STEP A: assign each data point to the nearest cluster center

2)STEP B:update each cluster center by replacing it with the mean of all points assigned to that cluster(in step A)

3)repeat step A & step B until the cluster converge to a stable solution
