Multi-class Support Vector Classifier
Welcome to the Multi-class Support Vector Classifier project! In this project, we will explore two popular approaches, namely, the one-against-one and one-against-all, to build a robust multi-class support vector classifier.

Problem Statement
The goal of this project is to create a powerful classifier that can accurately classify various classes from the MNIST dataset. We will train the classifier using the one-against-one and one-against-all approaches and compare their performances.

One-Against-One Approach
The one-against-one approach involves training multiple binary classifiers, each trained to distinguish between a pair of classes. In total, we will create C(C-1)/2 binary classifiers, where C is the number of classes in the dataset. During testing, each classifier predicts the class, and the class with the most votes becomes the final prediction.

One-Against-All Approach
In the one-against-all approach, we train C binary classifiers, where each classifier separates one class from the rest. During testing, we evaluate each classifier, and the class with the highest confidence score becomes the final prediction.
