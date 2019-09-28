# Un-SupervisedLearning
Vast majority of the available data is actually unlabeled: we have the input features X, but we do not have the labels y. 
Unsupervised learning is a solution of this problem.

Unsupervised learning tasks and algorithms:

• Clustering: the goal is to group similar instances together into clusters. This is a great tool for data analysis,
customer segmentation, recommender systems, search engines, image segmentation, semi-supervised learning, dimensionality reduction,
and more.

• Anomaly detection: the objective is to learn what “normal” data looks like, and use this to detect abnormal instances,
such as defective items on a production line or a new trend in a time series.

• Density estimation: this is the task of estimating the probability density function (PDF) of the random process that generated
the dataset. This is commonly used for anomaly detection: instances located in very low-density regions are likely to be anomalies. 
It is also useful for data analysis and visualization.


We will start with clustering, using K-Means and DBSCAN, and then we will discuss Gaussian mixture models and see how they can be used 
for density estimation, clustering, and anomaly detection.


