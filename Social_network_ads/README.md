# Social Network Ads

* This dataset contains information of users in a social network. Those informations are the user id, gender, age and the estimated salary. 
* A car company has just launched their brand new luxury SUV. And we're trying to see which of these users of the social network are going to buy this brand new SUV.
* The last column here tells if the user purchased this SUV or not. '0' refers to not purchased and '1' refers to purchsed. 
* We are going to build a model that is going to predict if a user is going to buy the SUV or not based on two variables which are age and the estimated salary.
* Each model is built in a separate python just to understand each of the models individually. 

### Models
The dataset is built upon Logistic Regression, K-Nearest Neighbors (KNN), Support vector machine (SVM), Decision trees and Random Forest.

### Metrics
Confusion matrix is used as a metric for performance evaluation.

***Confustion Matrix***

A confusion matrix is a NxN matrix used for evaluating the performance of a classification model, where N is the no of classes. 
The matrix compares the actual target values with those predicted by the ML model. For a binary classification, the confusion matrix is as shown below.

![alt text](https://github.com/rasunag27/ML_Projects/blob/main/Social_network_ads/confusion_matrix.JPG?raw=true)

In the above matrix,

* *True Positive (TP)*: The actual value is positive and the predicted value is positive.
* *True Negative (TN)*: The actual value is negative and the predicted value is negative.
* *False Positive (FP)*: The predicted value is falsely predicted. Here, the actual value is negative while the predicted value is positive.
* *False Negative (FN)*: The predicted value is falsely predicted. Here, the actual value is positive while the predicted value is negative.

Confusion matrix is a good evaluation metric compared to accuracy. Accuracy will be biased when it comes to imbalanced dataset.

### Visualization
For each of the model, I have created visualization for both training and testing dataset from which we can see a clear distinction visually of the target values.
