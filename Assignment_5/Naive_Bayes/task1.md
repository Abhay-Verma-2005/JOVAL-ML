# Task 1: Theory Questions 

## 1. What is the core assumption of Naive Bayes? <br>

    The core assumption is that all features (predictors) are conditionally independent given the class label. Despite being "naive," this simplification often performs well in practice, especially for text classification tasks.
## 2. Differentiate between GaussianNB, MultinomialNB, and BernoulliNB. <br>


#### GaussianNB
    Assumes the features follow a normal distribution.

    Ideal for datasets with continuous variables like sensor readings or measurements.

    Computes likelihood using the Gaussian probability density function.
#### MultinomialNB
    Models the counts of discrete features (e.g., term frequencies in text classification).

    Widely used in NLP tasks like spam filtering or document classification.
   
    Feature values must be non-negative integers.
#### BernoulliNB
    Treats features as binary indicators—whether a feature is present or not.
   
    Useful when presence/absence matters more than quantity (e.g., keywords in email classification)
   
    Sometimes outperform MultinomialNB if the dataset is highly sparse and binary.


## 3. Why is Naive Bayes considered suitable for high-dimensional data? <br>

    Its simplicity and efficiency stem from the conditional independence assumption, which avoids the curse of dimensionality. This makes it highly effective for tasks like spam detection or text categorization, where feature vectors are large.
