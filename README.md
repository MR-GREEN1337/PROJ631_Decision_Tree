[Link to a well-curated LInk](https://colab.research.google.com/drive/1RzSXARrodfAzv6iRJQQ5UKKswmadV0F6)


# 🌳 Decision Tree Classifier 🌳

Welcome to the Decision Tree Classifier project! 🎉

## Usage

To execute the file, simply open a codespace or download it locally and execute step by step.

## What is a Decision Tree?

A decision tree is a supervised machine learning algorithm used for both classification and regression tasks. It works by partitioning the data into smaller subsets based on certain features. These subsets are recursively split into further subsets until a stopping criterion is met, such as reaching a maximum depth or no further improvement in impurity reduction.

### How it Works

1. **Splitting**: The decision tree algorithm starts with the entire dataset and splits it into subsets based on the feature that provides the best split according to some criterion, typically maximizing information gain or minimizing impurity.

2. **Recursive Partitioning**: This process continues recursively for each subset, forming a tree-like structure where each node represents a feature and each branch represents a decision based on that feature.

3. **Stopping Criterion**: The splitting process continues until a stopping criterion is met, such as reaching a maximum depth, having a minimum number of samples in a node, or when further splitting does not significantly improve the model.

4. **Prediction**: Once the tree is built, new data points can be classified by traversing the tree from the root node to a leaf node, where a class label is assigned based on the majority class of the samples in that leaf node.

## Implementation Details

In this project, I implemented a Decision Tree Classifier using the CART (Classification and Regression Trees) algorithm. However, it's important to note that there was a slight hiccup during the implementation process. Initially, I overlooked the fact that I should implement the ID3 (Iterative Dichotomiser 3) algorithm, which is more suitable for classification tasks and handles categorical data better.

