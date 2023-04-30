# NLP-PROJECT

Accuracy:
SVC-91%,
Random forest-87%,
k-NN -84%,
LR-91%,
Naive Bayes-86%.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
Explanation for the accuracy:

The accuracy of a machine learning model depends on several factors, such as the quality of the data, the choice of algorithm, and the model's hyperparameters. In the given notebook, several models were trained to predict the sentiment of Amazon customer reviews for the "PC" product category. 

The highest accuracy scores were achieved by the Linear Support Vector Classifier (SVC) and Logistic Regression (LR) models, both achieving an accuracy of 91%. These models are often used in text classification tasks due to their ability to handle high-dimensional data and complex decision boundaries. 

The Random Forest model achieved an accuracy of 87%, which is also relatively high. Random Forest is an ensemble model that combines multiple decision trees, and it is known to be a robust and accurate model for a wide range of problems.

The K-Nearest Neighbors (KNN) model achieved an accuracy of 84%, which is lower than the other models. KNN is a relatively simple model that works by finding the closest data points to a given point and using their labels to predict the label of the new point. However, it may not perform well in high-dimensional data, such as text data.

The Naive Bayes model achieved an accuracy of 86%, which is also lower than the top two models. Naive Bayes is a probabilistic model that assumes independence between the features, and it is often used in text classification tasks due to its simplicity and efficiency.

In summary, the high accuracy scores achieved by SVC and LR models can be attributed to their ability to handle high-dimensional text data and their ability to learn complex decision boundaries. Random Forest and Naive Bayes models also performed well but not as good as the top two models.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Models used:

1. Support Vector Classifier (SVC):
The Support Vector Classifier (SVC) is a classification algorithm that uses a hyperplane to separate classes in the data. It tries to maximize the margin between the classes, which helps improve the generalization of the model. Some advantages of SVC are that it can work well on high-dimensional data and can handle non-linearly separable data using a kernel trick. However, SVC can be sensitive to the choice of kernel and regularization parameter C. Also, SVC may not perform well on very large datasets.

2. Random Forest:
Random Forest is a type of ensemble learning algorithm that creates multiple decision trees and combines their predictions to make a final prediction. Random Forests can handle high-dimensional data and can work well on both classification and regression tasks. They can handle missing data and are less prone to overfitting than decision trees. However, Random Forests can be slow to train and can be sensitive to the number of trees in the forest.

3. K-Nearest Neighbors (KNN):
K-Nearest Neighbors (KNN) is a classification algorithm that works by finding the K closest training examples in the feature space and predicting the most common class among those K examples. KNN can handle non-linearly separable data and can work well with small datasets. However, KNN can be sensitive to the choice of K and can be computationally expensive when dealing with large datasets.

4. Logistic Regression (LR):
Logistic Regression (LR) is a classification algorithm that works by fitting a logistic function to the training data. It can handle both binary and multi-class classification problems and is computationally efficient. LR also provides a probabilistic interpretation of the predictions. However, LR can be sensitive to outliers and may not perform well on non-linearly separable data.

5. Naive Bayes:
Naive Bayes is a classification algorithm that uses Bayes' theorem to predict the probability of a certain class given a set of features. Naive Bayes can handle high-dimensional data and is computationally efficient. It can work well on text classification problems and is less prone to overfitting. However, Naive Bayes assumes independence among the features, which may not always be true in practice.
