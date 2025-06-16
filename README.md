# Predicting-Consumer-Churn-with-Ensemble-Learning
Ensemble learning is a Machine Learning technique that utilizes multiple learners/models to make better predictions. Two common ensemble learning methods are Gradient Boosting and Random Forest. These models are especially good with larger datasets, like the Consumer Churn dataset, which has 10000 rows of data.
The churn dataset provides information about a person at a specific bank, including their location, bank balance, salary, and other relevant details. The dataset, once transformed, has a very large number of features, which is why these ensemble learning techniques can help by reducing variance and combining a multitude of predictors (decision trees).

# Data Preprocessing
The first step of this project is transforming the data, mainly into training and testing sets. First, we have to transform all categorical columns/features into their separate boolean columns. certain features like "satisfaction score" and "tenure" take a numeric form, but are really categorical, so they must also be transformed. We can then split the data into training and test splits to feed into our models.

## Decision Trees
To first explain Random Forests and Gradient Boost models, we must first understand what a decision tree is. Simply, a decision tree is just a sequence of questions until a prediction has been reached. The model starts with the dataset at the root node, and then chooses important features to split the data into smaller subsets. This splitting process continues until a leaf node is reached, where a prediction is eventually made.
![Image](https://github.com/user-attachments/assets/8d5aa862-e53e-474f-b8e5-c4419660fc14)


