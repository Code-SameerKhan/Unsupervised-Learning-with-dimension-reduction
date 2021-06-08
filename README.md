# Unsupervised Learning with Dimension Reduction

Unsupervised learning as the name suggests works on datasets where there is no label to classify or regress the target.\
The algorithm identify the patterns and tries to deduce the common characterstics between the data points.


# Major Unsupervised learning algorithms
* Clustering algorithms
1. KMeans
2. DBSCAN

#### KMeans
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each 
observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells.

k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.

#### DBSCAN
Density-based spatial clustering of applications with noise (DBSCAN) is a data clustering algorithm proposed by Martin Ester, Hans-Peter Kriegel, Jörg Sander and Xiaowei Xu 
in 1996. It is a density-based clustering non-parametric algorithm: given a set of points in some space, it groups together points that are closely packed together (points 
with many nearby neighbors), marking as outliers points that lie alone in low-density regions (whose nearest neighbors are too far away). DBSCAN is one of the most 
common clustering algorithms and also most cited in scientific literature.


* Gaussian Mixtures

Gaussian Mixture Models (GMMs) assume that there are a certain number of Gaussian distributions, and each of these distributions represent a cluster. 
Hence, a Gaussian Mixture Model tends to group the data points belonging to a single distribution together. Commonly used for anomaly detection.

It considers each cluster as having a unique and its own gaussian distribution (Bell shaped curve) withs its own statistical information.

