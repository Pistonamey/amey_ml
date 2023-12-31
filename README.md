# amey_ml

## Overview

amey_ml is a versatile Python machine learning package providing a range of algorithms for different kinds of data processing and machine learning tasks. It includes implementations of popular algorithms such as Naive Bayes, Linear Regression, Neural Networks using Keras, Decision Trees, K-Nearest Neighbors, and K-Means Clustering. This package is designed to be user-friendly, efficient, and easily integrable into data analysis pipelines.

## Installation

To install amey_ml, simply run the following command:

```python
pip install amey_ml
```

## Features
amey_ml includes the following modules and functions:

1. Naive Bayes (naive_bayes.py)
    - output(training_file, test_file): Perform Naive Bayes classification.

2. Linear Regression (linear_regression.py)
    - output(training_file, test_file, degree, lambda1): Perform regularized linear regression.

3. Neural Networks with Keras (nn_keras.py)
    - output(directory, dataset, layers, units_per_layer, epochs): Train and evaluate neural network models.

4. Decision Trees (decision_tree.py)
    - output(train_path, test_path, model_type, threshold): Train decision trees or random forests.

5. K-Nearest Neighbors (knn_classify.py)
    - output(training_file, test_file, k): Implement K-nearest neighbors classification.

6. K-Means Clustering (k_means.py)
    - output(data_file, K, initialization): Perform K-means clustering on a dataset.

Each function is designed to be straightforward to use, requiring only the necessary parameters for each specific algorithm.

Installing this package will install scikit-learn, tensorflow, pandas, scikit-learn, and keras by default.

## Usage
To use amey_ml, first import the required function from the package and then call it with the necessary parameters. Here are some example usages:
```python
from amey_ml import naive_bayes, linear_regression, nn_keras
from amey_ml import decision_tree, knn_classify, k_means

# Naive Bayes
naive_bayes.output('training_data.csv', 'test_data.csv')

# Linear Regression
linear_regression.output('train.csv', 'test.csv', 2, 0.01)

# Neural Networks using Keras
nn_keras.output('data_directory/', 'dataset_name', 3, 64, 10)

# Decision Trees
decision_tree.output('train_data.csv', 'test_data.csv', 'optimized', 0.05)

# K-Nearest Neighbors
knn_classify.output('train.csv', 'test.csv', 5)

# K-Means Clustering
k_means.output('data.csv', 3, 'random')

```

## Documentation
Each function in the amey_ml package comes with detailed docstrings explaining the functionality, 
parameters, and return types. For more detailed documentation, refer to the docstrings within each function.

## Contributing
Contributions to amey_ml are welcome! If you'd like to contribute, please contact me at amey.shinde@bizzencecollab.com. Please fork the repository and use a 
feature branch. Pull requests are warmly welcome.

## Licensing
The code in this project is licensed under MIT license.

## GitHub
https://github.com/Pistonamey/amey_ml/
