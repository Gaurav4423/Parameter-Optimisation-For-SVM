# Parameter Optimization of SVM
This is the assignment for course UCS654 presented by Gaurav Gupta (102197018)

## Introduction

Parameter optimization is a critical step in maximizing the performance of support vector machines (SVMs) for classification tasks. The two key parameters that need to be optimized in SVMs are the regularization parameter (C) and the kernel parameter (γ).
We can fine-tune these parameters to achieve Best Accuracy. The regularization parameter controls the trade-off between the complexity of the decision boundary and the level of misclassification, while the kernel parameter controls the flexibility of the decision boundary.
One common approach to parameter optimization is grid search, which involves searching over a predefined set of parameter values to find the optimal combination that maximizes the performance on a validation set. Now, we will be doing this using GridSearchCV for optimizing the parameters.
We will also be using Fitness Function .

## Dataset

TUANDROMD ( Tezpur University Android Malware Dataset)
https://archive.ics.uci.edu/ml/machine-learning-databases/00622/

The target attribute for classification is a category (GoodWare or Malware)

Number of Instances: 5464

Number of Attributes: 241

## Result

![image](https://user-images.githubusercontent.com/74859766/233193796-6c26cbfb-2a92-4065-9298-82b13a6e6837.png)

## Convergence Graph
![image](https://user-images.githubusercontent.com/74859766/233187136-57506e95-4827-48f3-a459-b8fc12f8422c.png)

## Conclusion
It concludes that as the number of iterations increases, the model becomes well trained and parameters have been optimised .
Sample 6 and 10 has the best accuracy of 0.9955.
