# Machine-Learning
This project has been created for the exam of Machine Learning of the Master's Degree course at the University of Turin.

The project is divided in 4 sections:
 - Decision Tree Models
 - Distance Based Models
 - Linear Models
 - Probabilistic Models

### Decision Tree Models
In this section there is the `iris_classification.ipynb`.
The purpose of this notebook is to manipulate the sk-learn iris dataset by applying transformations to the data within it and training different Decision Tree classifiers.

<p align="center">
  <img src="https://github.com/lorenzofavaro/Machine-Learning/blob/main/docs/decision-tree.png"/>
</p>

Then we analyze the performance of the classifiers according to different metrics including the accuracy score, f1 score and plotting the ROC curves.

### Distance Based Models
In this section we find two python notebooks.

In `iris_classification_knn.ipynb` we compare the prediction results obtained by decision trees and k-nearest neighbors on the dataset Iris. We use different types of weight (uniform or distance) to test prediction accuracy of k-nn and we verify which is the best k to choose for the (split) dataset at hand.

Finally we test and tune the gamma hyperparameter of a Radial Basis Function (RBF) Kernel used in k-nn as weight between data-points.

<p align="center">
  <img src="https://github.com/lorenzofavaro/Machine-Learning/blob/main/docs/knn.png"/>
</p>

In `clustering.ipynb` we use and compare different clustering algorithms: K-means and DBScan.

<p align="center">
  <img src="https://github.com/lorenzofavaro/Machine-Learning/blob/main/docs/clustering.png"/>
</p>

### Linear Models
In this section we apply the support vector machines to an artificial dataset built by my professor.

### Probabilistic Models
In this section we compare two models for categorical data probabilistic modeling: 
1. multivariate Bernoulli 
2. multinomial on a dataset 

We adopt a dataset on Twitter messages labelled with emotions (Joy vs Sadness).

## Setup
- Clone repository
- Create a virtual environment and activate it
- Install all the required libraries (you find the `requirements.txt` for each section) through `pip install -r requirements.txt`
- Open and launch any notebook

## Contributing
Libraries used:
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [scipy](https://scipy.org/)
- [seaborn](https://seaborn.pydata.org/)
- [matplotlib](https://matplotlib.org/)

## Author
[Lorenzo Favaro](https://github.com/lorenzofavaro)
