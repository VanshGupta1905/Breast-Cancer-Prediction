# Breast-Cancer-Prediction

## Project Goals
Data Exploration: Gain insights into the relationships between different features and breast cancer diagnosis.
Prediction: Develop accurate models to classify whether a tumor is malignant (cancerous) or benign (non-cancerous).
Model Optimization: Experiment with different algorithms and techniques to find the most effective predictive approach.

## Data Understanding: 
Visualize and analyze the relationships between features and breast cancer diagnosis using:
Box Plots
Heatmaps
Histograms
Machine Learning: Apply various algorithms:
PCA (Principal Component Analysis)
Logistic Regression
Decision Trees
Random Forests
Gradient Boosting
Deep Learning: Build neural networks:
Baseline Model (No Regularization/Dropout)
Regularized Model
Deep Model with Increased Layers and Regularization

pen_spark

# Step 1
Box Plots: Visualize the spread of feature values and identify potential outliers.
Heatmap: Explore correlations between different features.
Histplots: Observe the distribution of individual features.

# Step 2
Applied several machine learning models to the data:

## PCA (Principal Component Analysis):
PCA is a dimensionality reduction technique. It helps simplify the data by identifying the most important combinations of features (principal components) that explain the most variance. This makes subsequent modeling more efficient.

## Logistic Regression: 
A fundamental algorithm for binary classification tasks like ours (malignant vs. benign). It estimates the probability that a given sample belongs to a particular class based on its features.<br>
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/a2cb030f-7ef5-4cdd-b0b6-dd675ccd4541)<br>
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/991f007e-b559-4660-a725-fcf293708314)

## Decision Trees: 
These models create a tree-like structure where each node represents a decision based on a feature, and each leaf represents a class prediction. They're easy to interpret but can be prone to overfitting.
<br>
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/4e9d0e99-4cee-4a7c-a802-7a86dadca749)
<br>
## Random Forests: 
An ensemble method that builds multiple decision trees, each trained on a random subset of data and features, and combines their predictions for improved accuracy and robustness.<br>
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/ddd210b7-eb8c-40e5-9390-176000795ce3)

## Gradient Boosting:
This is an ensemble method, meaning it combines multiple weak learners (like decision trees) to create a stronger model. Gradient Boosting works by iteratively adding models that focus on the errors made by the previous ones, leading to improved accuracy.<br>
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/a4be7f83-0995-4de5-ab8a-8b4b0d40370a)



# Deep Learning Models

### We then explored the potential of neural networks for breast cancer detection:

## Baseline Model: A simple neural network with no regularization or dropout.
### Model Summary
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/a71c6514-5a14-4347-8886-f742eeb9cba6)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/0b86854e-8f3c-4a5e-b09d-4ffb6fc2dc5e)


## Regularized Model: Added L1/L2 regularization and dropout to prevent overfitting.
### Model Summary
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/863faa11-9692-45e7-9360-d1dd6945b441)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/6461bb6e-ec17-412c-8e31-48b75163d32c)


## Deep Model: Increased the number of layers, dropout rate, and regularization for potentially better generalization.

### Model Summary 
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/e229806a-8cb3-4030-8298-b0f4d5ee0ea6)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/71497abd-1030-4fdd-9251-08b2c3442c56)




