# Breast-Cancer-Prediction

## Project Goals
Data Exploration: Gain insights into the relationships between different features and breast cancer diagnosis.
Prediction: Develop accurate models to classify whether a tumor is malignant (cancerous) or benign (non-cancerous).
Model Optimization: Experiment with different algorithms and techniques to find the most effective predictive approach.

# Step 1
Box Plots: Visualize the spread of feature values and identify potential outliers.
Heatmap: Explore correlations between different features.
Histplots: Observe the distribution of individual features.

# Step 2
Applied several machine learning models to the data:

## PCA (Principal Component Analysis):
PCA is a dimensionality reduction technique. It helps simplify the data by identifying the most important combinations of features (principal components) that explain the most variance. This makes subsequent modeling more efficient.

## Logistic Regression: 
A fundamental algorithm for binary classification tasks like ours (malignant vs. benign). It estimates the probability that a given sample belongs to a particular class based on its features.
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/a2cb030f-7ef5-4cdd-b0b6-dd675ccd4541)
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/991f007e-b559-4660-a725-fcf293708314)

## Decision Trees: 
These models create a tree-like structure where each node represents a decision based on a feature, and each leaf represents a class prediction. They're easy to interpret but can be prone to overfitting.

## Gradient Boosting:
This is an ensemble method, meaning it combines multiple weak learners (like decision trees) to create a stronger model. Gradient Boosting works by iteratively adding models that focus on the errors made by the previous ones, leading to improved accuracy.

# Deep Learning Models

### We then explored the potential of neural networks for breast cancer detection:

### Baseline Model: A simple neural network with no regularization or dropout.
### Model Summary
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/a71c6514-5a14-4347-8886-f742eeb9cba6)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/224c0f32-e5de-4891-8006-6906b1f3c037)

Regularized Model: Added L1/L2 regularization and dropout to prevent overfitting.
### Model Summary
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/863faa11-9692-45e7-9360-d1dd6945b441)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/6461bb6e-ec17-412c-8e31-48b75163d32c)
Deep Model: Increased the number of layers, dropout rate, and regularization for potentially better generalization.

### Model Summary 
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/e229806a-8cb3-4030-8298-b0f4d5ee0ea6)
### Model Performance
![image](https://github.com/VanshGupta1905/Breast-Cancer-Prediction/assets/97848559/c5106cb3-6efe-4df7-9b7f-25d88f8a4f8b)




