# Predicting-Consumer-Churn-with-Ensemble-Learning
Ensemble learning is a Machine Learning technique that utilizes multiple learners/models to make better predictions. Two common ensemble learning methods are Gradient Boosting and Random Forest. These models are especially good with larger datasets, like the Consumer Churn dataset, which has 10000 rows of data.
The churn dataset provides information about a person at a specific bank, including their location, bank balance, salary, and other relevant details. The dataset, once transformed, has a very large number of features, which is why these ensemble learning techniques can help by reducing variance and combining a multitude of predictors (decision trees).

# Data Preprocessing
The first step of this project is transforming the data, mainly into training and testing sets. First, we have to transform all categorical columns/features into their separate boolean columns. certain features like "satisfaction score" and "tenure" take a numeric form, but are really categorical, so they must also be transformed. We can then split the data into training and test splits to feed into our models.

## Decision Trees
To first explain Random Forests and Gradient Boost models, we must first understand what a decision tree is. Simply, a decision tree is just a sequence of questions until a prediction has been reached. The model starts with the dataset at the root node, and then chooses important features to split the data into smaller subsets. This splitting process continues until a leaf node is reached, where a prediction is eventually made.

![Image](https://github.com/user-attachments/assets/5d4f9d0c-6fb6-40df-8dc3-8384b0b8a8f8)

## Random Forest
The random forest algorithm utilizes multiple decision trees, independent from each other, to make predictions on random subsets of the training data. Random Forests use a process called bagging to train subsets of the data. 

![Image](https://github.com/user-attachments/assets/fcbde255-b55d-48c2-a609-900927f4e547)

## Gradient Boosting
The Gradient Boost Model is similar to the Random Forest algorithm, however uses a slightly different process called boosting. This means, results are aggregated throughout the algorithm's process instead of at the end. Each tree used in the algorithm is built on the previous tree's errors, and this gives it the power to learn complex patterns in the data.
