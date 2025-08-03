# Part-III: Ensemble Learning – Bagging, Boosting, Random Forest 

## Objective: 
To understand and implement ensemble techniques like Random Forest, 
AdaBoost, and Gradient Boosting for improving classification performance.

### 1. What is the difference between Bagging and Boosting?

    Bagging (Bootstrap Aggregating): Trains multiple models independently on different random subsets of the data and averages their predictions. It reduces variance.

    Boosting: Trains models sequentially, where each model tries to correct the errors of the previous one. It reduces bias but can be prone to overfitting.

### 2. How does Random Forest reduce variance?

    Random Forest uses bagging and feature randomness. By training many decision trees on bootstrapped samples and averaging their predictions, it smooths out fluctuations and reduces overfitting caused by high variance in individual trees.

### 3. What is the weakness of boosting-based methods?

    Boosting can be sensitive to noisy data and outliers, since it focuses heavily on correcting previous mistakes. This can lead to overfitting, especially if the model is too complex or trained for too many iterations.