# Ensemble Learning and Random Forests

This repository contains practical examples and experiments with **Ensemble Learning** techniques using **Scikit-Learn**. The notebook demonstrates how combining multiple machine learning models can improve predictive performance, reduce overfitting, and increase model robustness.

## Topics Covered

### Voting Classifiers

* Hard and soft voting strategies
* Combining multiple classifiers:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine (SVM)
* Performance comparison using accuracy metrics

### Bagging and Pasting

* Bootstrap Aggregating (Bagging)
* Comparison with a single Decision Tree
* Effect of ensemble methods on model stability and accuracy

### Random Forests

* Training and evaluating Random Forest classifiers
* Understanding the relationship between Bagging and Random Forests
* Hyperparameter configuration and model optimization

### Feature Importance

* Measuring feature importance with Random Forests
* Analysis using the Iris dataset
* Interpretation of feature contribution scores

### Boosting

* AdaBoost implementation
* Weak learners with Decision Trees
* Impact of learning rate and number of estimators

### Gradient Boosting (Regression)

* Sequential error correction
* Decision Tree Regressors
* Building stronger predictive models through boosting

## Technologies Used

* Python
* NumPy
* Scikit-Learn
* Jupyter Notebook

## Dataset Examples

The notebook uses:

* Synthetic datasets generated with `make_moons()`
* The Iris dataset from Scikit-Learn
* Randomly generated regression datasets

## Learning Objectives

After completing this notebook, you will understand:

* The motivation behind ensemble learning
* Differences between Bagging, Random Forests, and Boosting
* How Voting Classifiers combine multiple models
* How to evaluate ensemble models
* How feature importance is calculated
* When to use different ensemble techniques in practice

## Repository Structure

```text
.
├── EL_and_RF.ipynb
└── README.md
```

## References

* Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow by Aurélien Géron
* Scikit-Learn Documentation
