# Creating Customer Segments

Unsupervised Learning (Clustering) Project of Udacity Machine Learning Engineer Nanodegree Program

Reviewed unlabeled data to understand the patterns. Applied unsupervised learning methods (PCA and KMeans) to cluster data into natural categories they fit into. Interpreted the findings.


## Project Overview

This project applies unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. It consists of the following tasks:

* Explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. 
* Preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. 
* With the good, clean customer spending data,
  - Apply PCA transformations to the data.
  - Implement clustering algorithms to segment the transformed customer data.
* Compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.


This project is designed to give a hands-on experience with unsupervised learning and work towards developing conclusions for a potential client on a real-world dataset. Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.



## Machine Learning Theory and Concept

* Unsupervised Learning: K-Means Clustering
* Principal Component Analysis (PCA)
* Feature Scaling: Use natural logarithmic scaling to transform a positively skewed variable into a normally distributed one. Useful for investigating correlations between variables.
* $R^2$ score as a measure for goodness of fit


## Technical Skills

* `sklearn.decomposition.PCA`: principal component analysis.
* `sklearn.cluster.KMeans`: K-Means clustering.
* `sklearn.metrics.silhouette_score`: select the number of clusters in K-Means clustering by maximizing this score.
* `sklearn.model_selection.train_test_split`: split labeled data into training and validation sets using stratified random sampling.
* `pandas.plotting.scatter_matrix`: use scatter matrix plot to investigate correlations between variables and distributions of variables.
* `seaborn.heatmap`: use heatmap to compare sample points to sample mean, for a multivariable dataset.


## Development Environment

* OpenSUSE Linux 42.2
* Anaconda 4.4 with Python 2.7
* pandas, numpy, sklearn

