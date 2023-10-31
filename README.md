# Logistic Regression for Decision Boundary

This repository contains the implementation of logistic regression models in a sample dataset for predicting admission into a university and microchip quality assurance (QA) using test results. The project also demonstrates feature mapping and regularization in logistic regression.

## Admission Prediction

In the first part of the exercise, logistic regression is used to predict whether a student gets admitted to a university based on their scores on two entrance exams. The goal is to build a classification model that estimates an applicant's probability of admission. A sample prediction is provided for a student with specific exam scores.

## Microchip QA

The second part of the exercise deals with logistic regression to predict whether microchips from a fabrication plant pass quality assurance. Test results for two different tests are used to determine whether the microchips should be accepted or rejected.

## Feature Mapping

To enhance model performance, feature mapping is introduced. This technique involves creating more features from each data point, resulting in a higher-dimensional feature vector. A logistic regression classifier trained on this vector can produce a more complex, nonlinear decision boundary.

## Regularization

To combat overfitting, regularization is applied to the logistic regression models. Different values of the regularization parameter (λ) are explored to observe the impact on decision boundaries. Regularization helps prevent overfitting, ensuring that the model generalizes well to new data.

## Visualization

The project includes a function called `plotDecisionBoundary` that visually represents the decision boundaries produced by the logistic regression models. By varying the regularization parameter, you can observe the changes in the decision boundary.

### Implementation Details

The relevant code files include:
- `logistic_regression.ipynb`: Jupyter Notebook logistic regression tasks.
- `utils.py`: Contains the `mapFeature` function for feature mapping and `plotDecisionBoundary` for visualization.
- Sample datasets: Training datasets used for the logistic regression tasks.