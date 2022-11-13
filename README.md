# Spam_email_classification_from_scratch
Performed preprocessing of data on 1500+ emails data set and presented the data into two different representation namely </br>
Bag of words and Bernoulli’s representation for using classification models</br>
 Executed 4 different algorithms: Multinomial Naive Bayes for Bag of Words representation, Discrete Naive Bayes for 
Bernoulli’s representation, Logistic Regression with L2 regularization and SGD Classifier for both representation</br>
 Manually implemented the algorithms except the SGDClassifier and used log scale for the calculations to avoid underflow</br>
 Used 1 Laplace smoothing in the Naive Bayes algorithms to tackle the problem of zero probability and Hyper tuned the 
learning rate parameter lambda for the logistic regression algorithm by splitting the training data into train and validation
