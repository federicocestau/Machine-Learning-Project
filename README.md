# Machine-Learning-Project

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, I created machine learning models capable of classifying candidate exoplanets from the raw dataset.These are classification models into three classes: Candidate, Confirmed and False Positive. 

For each model I splitted the data into train data to fit the model and test data to test how good it's each one. I have multiple columns that are the X_Values (Independent Variables) and one Column with the classes that is my Y, dependent variable. Once it is splitted I scaled my X Data. 
Models used: 

1) Logistic Regression: Is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary,e.g., presence vs. absent).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.Multinomial logistic regression is a form of logistic regression used to predict a target variable have more than 2 classes. It is a modification of logistic regression using the softmax function instead of the sigmoid function. 

2) SVM: The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points.Our objective is to find a hyperplane that has the maximum margin, i.e the maximum distance between data points of both classes. Maximizing the margin distance provides some reinforcement so that future data points can be classified with more confidence.

3) Random Forest: Like its name implies, consists of a large number of individual decision trees that operate as an ensemble. Each individual tree in the random forest spits out a class prediction and the class with the most votes becomes our model’s prediction. A large number of relatively uncorrelated models (trees) operating as a committee will outperform any of the individual constituent models.

4) KNN : The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.To select the K that’s right for your data, we run the KNN algorithm several times with different values of K and choose the K that reduces the number of errors we encounter while maintaining the algorithm’s ability to accurately make predictions when it’s given data it hasn’t seen before. Find the optmize K value it is the challenge to make the algorithm as accurate as possible. 

5) Deep Learning: It is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called artificial neural networks.For images classification and data that is difficult and complex to make a "line division" in order to classify it, Deep Learning might be the best model. 

In this example the best model to use in order to predict the Y data (Dependent Variable) it is the Random Forest with an score in our testing data of 0.89!



