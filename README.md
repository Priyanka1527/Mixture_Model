# Probably Interesting Data
#### Submitted by: Priyanka Saha

EECS 738 Project - The goal of this project is to develop a mixture model for modelling data from 2 different datasets without using any default Machine Learning library.

# Problem Statement:
1. Set up a new git repository in your GitHub account
2. Pick two datasets from https://www.kaggle.com/uciml/datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to model distributions within the dataset
5. Build a heuristic and/or algorithm to model the data using mixture models of probability distributions programmatically
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub

# Datasets:
- Iris
- Glass Classiciation

# Possible Machine Learning Applications:
- Iris Dataset:
  - Prediction of the class of Iris based on the features
  
- Glass Classification:
  - Prediction of the Glass types using the features
  - Principle component analysis of glass and feature importance
  
# Mixture Model creation Approach:
GMM was attempted to be developed using simple probability and distance functions and then utilizing Expectation-Maximization concept. The number of initial clusters were pre-assumed for this assignment. The algorithm initially assumes parameters of the model and then maximizes them by applying to a function. Afterwards, it uses the updated maximised parameters and continue the cycle untill convergence. The same approach was applied to both of the datasets and stepwise explanations were given and comments added under **Iris - Mixture Model.ipynb**.
