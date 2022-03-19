<h1 align="center">Clustering</h1><br>
Clustering is the task of dividing the population or data points into a number of groups (Clusters) such that data points in the same groups are more similar to other data points in the same group than those in other groups. In simple words, the aim is to segregate groups with similar traits and assign them into clusters.

<img src="images/Clustering example.jpg"></img>

### KMeans: <br>

K means is an iterative clustering algorithm that aims to find local maxima in each iteration. This algorithm works in these 5 steps :
- Specify the desired number of clusters K.
- Randomly assign each data point to a cluster.
- Compute cluster centroids.
- Re-assign each point to the closest cluster centroid.
- Re-compute cluster centroids.

**We need to achieve:**
- Minimum distance between points in a cluster.
- Maximum distance between clusters (Centroids).
