# How to Learn Machine Learning Algorithms for Interviews?

## Naive Bayes Classifier?

Theoretical Understanding:

1. https://www.youtube.com/watch?v=jS1CKhALUBQ
2. https://www.youtube.com/watch?v=temQ8mHpe3k

### 1. What are the Basic Assumption?
Features are independent.

### Advantages
1. Works very well with many number of features.
2. Works well with large training dataset.
3. It converges faster when we are training the model.
4. It also performs well with categorical features.

### Disadvantages
1. Correlated features affects performance.


### is Feature Scaling required?
No

### Impact of Missing values?
Naive Bayes can handle missing data. Attributes are handles seperately by the algorithm at both model construction time and prediction time. As such, if a data instance has a missing value fora an attribute, it can be ignored while preparing the model, and ignored when a probability is calcualted for a class value.


### Impact of outliers?
It is usually robust to outliers.

### Different Problem statement you can solve using Naive Baye's
1. Sentiment Analysis.
2. Spam classification.
3. Twitter sentiment analysis.
4. NLP

### Why Naive Bayes is used in NLP Problems?
Naives Bayes are mostly used in NLP. Naive bayes predict the tag of a text. They calculate the probability of each tag for a given text and then output the tage with the highest one.
