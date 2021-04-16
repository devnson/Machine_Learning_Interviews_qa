# SVM

Tutorials:

1. https://www.youtube.com/watch?v=H9yACitf-KM
2. https://www.youtube.com/watch?v=Js3GLb1xPhc


## What are the Basic Assumption?
There are no such assumptions.

## Advantages
1. SVM is more effective in high dimensional spaces.
2. SVM is relatively memory efficient.
3. SVM's are very good when we have no idea on the data.
4. Works well with even unstructured and semi strucuted data like text, images and trees.
5. The kernel trick is real strength of SVM. With an appropriate kernel function, we can solve any complex problem.
6. SVM models have generalization in practice, the risk of over-fitting is less in SVM.


## Disadvantages
1. More trainig time is required for larger dataset.
2. It is difficult to choose a kernel function https://www.youtube.com/watch?v=mTyT-oHoivA
3. The SVM hyper parameters are Cost- C and gamma. It is not that easy to fine-tune these hyper-parameters. It is hard to visualize their impact.

## Whether Feature Scaling is required?
Yes

## Impact of Missing values?
Although SVMs are an attractive option when constructing a classifier, SVMs do no easily accommodate missing covariate information. Similar to other prediction and classification methods, in-attention to missing data when constructing an SVM can impact the accuracy and utility of the resulting classifier.

## Impact of outliers

It is usually sensitive to outliers https://arxiv.org/abs/1409.0934#:~:text=Despite%20its%20popularity%2C%20SVM%20has,causes%20the%20sensitivity%20to%20outliers.

## Types of Problems it can solve 
1. Classification
2. Regression

## Overfitting and Underfitting
In SVM, to avoid overfitting, we choose a Soft Margin, instead of a Hard one i.e. we let some data points enter our margin intentionally (but we still penalize it) so that our classifier don't overfit on our training sample

## Different Problem statement you can solve using Naive Baye's
1. We can use SVM with every ANN usecases.
2. Intrusion Detection.
3. Handwriting Recognition.

## Performance Metrics

### Classification
- Confusion Matrix
- Precision,Recall, F1 score

### Regression
- R2,Adjusted R2
- MSE,RMSE,MAE
