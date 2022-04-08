# GLASS CLASSIFICATION USING KNN ALGORITHM
### Machine Learning Prediction and Classification

__Objective:__

To classify the type of glasses based on their physical and chemical properties.

__Methodogoly__:
The dataset is collected from the UCI Machine learning repository. The dataset is cleaned and done with feature scaling before working with ML algorithm. The columns of the dataset are:
 * RI: Refractive index
 * Na: Sodium
 * Mg: Magnesium
 * Al: Aluminium
 * Si: Silica
 * K: Potassium
 * Ca: Calcium
 * Ba: Barium
 * Fe: Iron
 * Types of glass (Target label).

The target label has 7 different classes such as:
 * Building window (float processed)
 * Building window (non float processed)
 * Vehicle window (float processed)
 * Vehicle window (non float processed)
 * Containers
 * Tablewraps
 * Headlamps

I have used KNN machine learning algorithm to classify the glasses. KNN is a supervised learning algorithm which considers K-Nearest Neighbors to predict the target class in classification. KNN works on the principle of distance based metrics. In this dataset, I have compared two different distance methods of KNN and found out which is the best outcome based on metric evaluation. More about KNN can be found in https://www.analyticsvidhya.com/blog/2021/04/simple-understanding-and-implementation-of-knn-algorithm/

__Metrics__:

I have used accuracy and classification report as metric for the evaluation of best distance method. I have also found out the best amount of nearest neighbors for the evaluation.
