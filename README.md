# Data-Science-and-Business-Analytics-Internship
This repository contains three basic models potraying Regression, Classification and CLustering techniques
## 1.Student_Score.ipynb
* Predicts the score of a student based on the number of hours spent for reading.
* Linear Regression model was built on the small dataset to predict the student score.

## 2.Decision_tree_iris.ipynb
* Predicts the type of flower based on 4 features (sepalLength,sepalWidth,petalLength,petalWidth) of a flower
* Decision tree technique was leveraged to find the type of iris flower
* Outliers are detected and removed from dataset through Box-plot and Guassian-distribution
* Accuracy on test_data : 97%

## 3.iris_unsupervised.ipynb
* Clusters the iris dataset into optimum number of clusters.
* K-Means Clustering algorithm works on the principle "Birds of feather flock together" i.e datapoints with similar features lie in colse proximity.
* Optimum number of clusters(K) can be found from the plot drawn with WCSS(Sum of Squares within the clusters)
* An optimal K will be with less WCSS but not very low(An elbow indication in plot of K vs WCSS)
