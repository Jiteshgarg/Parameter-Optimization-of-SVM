# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

This dataset is used for research aimed at the case of customers default payments and compares the predictive accuracy of probability of default among six data mining methods. It is a multi-variate classification Dataset.

Number of Instances: 30000

Number of Attributes: 24

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.78 | rbf | 6.31 | 1.46 |
| 2 | 0.78 | sigmoid | 1.76 | 3.78 |
| 3 | 0.78 | rbf | 4.68 | 3.00 |
| 4 | 0.79 | rbf | 4.68 | 1.76 |
| 5 | 0.77 | sigmoid | 8.06 | 4.96 |
| 6 | 0.70 | linear | 6.66 | 8.12 |
| 7 | 0.77 | rbf | 1.47 | 3.71 |
| 8 | 0.78 | rbf | 7.71 | 7.20 |
| 9 | 0.78 | sigmoid | 1.61 | 0.91 |
| 10 | 0.62 | poly | 6.61 | 7.10 |


## Convergence Graph
![graph](https://github.com/Jiteshgarg/Parameter-Optimization-of-SVM/blob/main/graph.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 4 has the best accuracy of 0.79 having kernel = rbf, Nu = 4.68 and Epsilon = 1.76.

## Written By
Name : Jitesh Garg
  
Roll No. : 102017180

Sub-Group: 3CS8
