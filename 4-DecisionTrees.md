# Decision Trees Classifier and Regressor

<b> Interview Questions </b>
- Decision Tree
- Entropy, Information Gain, Gini Impurity
- Decision Tree working for Categorical and Numerical Features.
- What are the scenarios where Decision Tree works well
- Decision Tree Low Bias and High Variance - Overfitting
- Hyperparamter Techniques.
- Library used for constructing decision tree.
- Impact of Outliers of Decision Tree
- Impact of missing values on Decision Tree.
- Does Decision Tree require Feature Scaling


<b> Theoretical Understanding </b>

1. Tutorial 37:Entropy In Decision Tree https://www.youtube.com/watch?v=1IQOtJ4NI_0
2. Tutorial 38:Information Gain https://www.youtube.com/watch?v=FuTRucXB9rA
3. Tutorial 39:Gini Impurity https://www.youtube.com/watch?v=5aIFgrrTqOw
4. Tutorial 40: Decision Tree For Numerical Features: https://www.youtube.com/watch?v=5O8HvA9pMew
5. How To Visualize DT: https://www.youtube.com/watch?v=ot75kOmpYjI


## What are the Basic Assumption?
There are no such assumptions.

## Advantages

1. Clear Visualization: The algorithm is simple to understand, interpret and visualize as the idea is mostly used in our daily lives. Output of a Decision Tree can be easily interpreted by humans.
2. Simple and easy to understand: Decision Tree looks like simple if-else statements which are very easy to understand.
3. Decisioni Tree can be used for both classification and regression problems.
4. Decision Tree can handle both continous and categorical variables.
5. No feature scaling required: No feature scaling (standardization and normalization) required in case of Decision Tree as it uses rule based approach instead of distance calcualtion.
6. Handles non-linear parameters efficiently: Non linear parameters dont' affect the performance of a Decision Tree unlike curve based algorithms. So, if there is high non-linearity between the independetn variables, Decision Trees may outperform as compared to other curve based algorithms.
7. Decision Tree can automatically handle missing values.
8. Deicsion Tree is usually robust to outliers and can handle then automatically.
9. Less Training Period: Training Period is less as compared to Random Forest because it generates only one tree unlike forest of trees in the Random Forest.


## Disadvantages
1. Overfitting: This is the main problem of the Decision Tree. It generally leads to overfitting of the data which ultimately leads to wrong predictions. In order to fit the data (even noisy data), it keeps generating new nodes and ultimately the tree becomes too complex to interpret. In this way, it loses its generalization capabilities. It performs very well on the trained data but starts making a lot of mistakes on the unseen data.
2. High variance: As mentioned in point 1, Decision Tree generally leads to the overfitting of data. Due to overfitting, there are very high chances of high variance in the output which leads to many errors in the final estimation and shows high inaccuracy in the results. In order to achieve zero bias (overfitting), it leads to high variance.
3. Unstable: Adding a new data point can lead to re-generation of the overall tree and all nodes need to be recalculated and recreated.
4. Not suitable for large datasets: If data size is large, then one single tree may grow complex and lead to overfitting. So in this case, we should use Random Forest instead of a single Decision Tree.

## is Feature Scaling required?
No

## Impact of Outliers?
It is not sensitive to outliers. Since, extreme values or outliers, never cause much reduction in RSS, they are never involved in split. Hence, tree based methods are insensitive to outliers.

## Types of Problems it can solve 
1. Classification
2. Regression


## How to avoid overfitting
https://www.youtube.com/watch?v=SLOyyFHbiqo&ab_channel=KrishNaik


## Performance Mertics

### Classification
1. Confusion Matrix
2. Precision, Recall, F1 Score

### Regressioin
1. R2, Adjusted R2
2. MSE, RMSE, MAE
