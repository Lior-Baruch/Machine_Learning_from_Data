# Machine Learning from Data

This repository contains implementations of various machine learning algorithms and concepts as part of the course "Machine Learning from Data" offered by Reichman University.

## Repository Structure and Detailed Overview

The repository is structured into multiple directories, each containing a Jupyter notebook implementing a specific machine learning algorithm or concept. Below is a detailed overview of each directory:

### Decision Trees (`Decision_Trees` directory)

This directory contains a Jupyter notebook (`hw2_Decision_Trees.ipynb`) implementing a Decision Tree algorithm for classification. The implementation uses the `DecisionTreeClassifier` from the scikit-learn library. The notebook includes data loading, exploratory data analysis, feature selection, model training and prediction, and evaluation of the model's performance. The `agaricus-lepiota.csv` dataset is used for this implementation.

### Linear Regression (`Linear_Regression` directory)

This directory contains a Jupyter notebook (`hw1_Linear_Regression.ipynb`) implementing Linear Regression for predicting a continuous outcome. The notebook walks through data loading, exploratory data analysis, model training using gradient descent, evaluation of the model's performance, and comparison of the custom implementation with scikit-learn's `LinearRegression` model. The `data.csv` dataset is used for this implementation.

### Logistic Regression, Bayes Classifier, and Expectation-Maximization (EM) algorithm (`Logistic_Regression_Bayes_and_EM` directory)

This directory contains a Jupyter notebook (`hw4_Logistic_Regression_Bayes_and_EM.ipynb`) that implements and compares three algorithms: Logistic Regression, Bayes Classifier, and the Expectation-Maximization (EM) algorithm. The notebook includes sections on data loading, exploratory data analysis, implementation and training of each model, comparison of the models' performance, and a final conclusion. The `training_set.csv` and `test_set.csv` datasets are used for these implementations.

### Maximum A Posteriori (MAP) Classifier (`MAP_Classifier` directory)

This directory contains a Jupyter notebook (`hw3_MAP_Classifier.ipynb`) implementing the Maximum A Posteriori (MAP) Classifier for classification tasks. The notebook includes data loading, exploratory data analysis, model training and prediction, and evaluation of the model's performance. The `data` directory contains the datasets used for this implementation.

## Usage

To run any of the implemented algorithms, navigate to the corresponding directory and open the respective Jupyter notebook. 

## Dependencies

The implementations use the following libraries:

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch

Ensure these libraries are installed in your Python environment to run the notebooks successfully.

## Contributors

The code in this repository was written by the students of the "Machine Learning from Data" course offered by Reichman University.

## License

The code in this repository is licensed under the MIT License.
