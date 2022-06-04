# Iris_dataset

## About dataset

The iris dataset is a famous dataset that contains the sepal and petal length and width of 150 iris flowers of three different species: Iris setosa, Iris versicolor and Iris virginica.

## Scope of the project

**Support vector machines (SVMs)** are a set of supervised learning methods used for classification, regression and outliers detection.

The advantages of support vector machines are:

  * Effective in high dimensional spaces.

  * Still effective in cases where number of dimensions is greater than the number of samples.

  * Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.

  * Versatile: different Kernel functions can be specified for the decision function. Common kernels are provided, but it is also possible to specify custom kernels.

The disadvantages of support vector machines include:

  * If the number of features is much greater than the number of samples, avoid over-fitting in choosing Kernel functions and regularization term is crucial.

  * SVMs do not directly provide probability estimates, these are calculated using an expensive five-fold cross-validation.

We tried to get used to the **Support Vector Machines**, training different models, tuning hyperparameters and gaining a better understanding of the SVMs.
**Task: Build a classifier to detect the Iris virginica type based only on the petal width feature.**

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib  
**ML Book:** https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291
