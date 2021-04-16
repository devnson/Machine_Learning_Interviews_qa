# Logistic Regression

<b> Theoretical Understanding </b>

1. Tutorial 35:Logitic Regression Part 1 https://www.youtube.com/watch?v=L_xBe7MbPwk
2. Tutorial 36:Logitic Regression Part 2 https://www.youtube.com/watch?v=uFfsSgQgerw
3. Tutorial 39:Logitic Regression Part 3 https://www.youtube.com/watch?v=V8fS0T_ktn4
4. Tutorial 42:How To Find Optimal Threshold for Binary classification: https://www.youtube.com/watch?v=_AjhdXuXEDE
5. Interview question: https://www.youtube.com/watch?v=tcaruVHXZwE&t=122s


## What are the Basic Assumption?
Linear Relationship between independent features and the log odds.


## Advantages
1. Logistic Regression are very easy to understand.
2. It required less training.
3. Good accuracy for many simple data sets and it performs well when the dataset is linearly  seperable.
4. It makes no assumptions about distributions of classes in feature space.
5. Logistic regression is less inclined to over-fitting but it can overfit in high dimesnional datasets. One may consider Regularization (L1 and L2) techniques to avoid over-fitting these scenarios.
6. Logistc Regression is easier to implement, interpret and very efficient to train.

## Disadvantges
1. Sometimes Lot of Feature Engineering is required.
2. If the independent features are correlated it may affect performance.
3. It is often quite prone to nose and overfitting.
4. If the number of observations is lesser than the number of features, Logistic Regression should not be used, otherwise it may lead to overfitting.
5. Non-linear problems can't be solved with logistic regression because it has a linear decision surface. Linearly seperable data is rarely found in real-world scenarios.
6. It it tough to obtain complex relationships using logistic regression. More powerful and compact algorithms such as Neural Networks can easily outperform this algorithm.
7. In Linear Regression independent and dependent variables are related linearly. But logistic regression needs that independent variables are linearly related to the log odds (log(p / (1 - p))


## Feature Scaling required?
Yes

## Missing values
Sensitive to missing values

## Impact of outliers?
Like linear regression, estimates of the logistic regression are sensitive to the unusual  observationis: outliers, high leverage, and influential observations. Numerial examples and analysis are presented to demonstrate the most recent outlier diagnostic methods using data sets from medical domain.

## Types of problems
Pure Classification

##  Performance metrics
1. Confusion Matrix
2. Preicision, Recall, F1 Score
3. ROC Curve, AUC Curve

