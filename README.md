# Fashion-Images-Classification-Logistic-Regression
The purpose of the project classify which fashion item is in the image.

# Data
We have 5000 images for training and 200 images for testing. They are stored in X_train.npy, y-train.npy, X_Test.npy, y_test.

There are 9 types of images related to fashion (T-Shirt/Top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag and Ankle Boot).

# Steps
Steps for classification of fashion images are the following:
- PCA (Principle Component Analysis) for dimentionality reduction.
- Training the data with Logistic Regression Model.
- Performing GridSearch on Logistic Regression's hyper-parameters to chose the best performing ones.

# Results
We get the following final resutls on test data:

**Acuracy:** Accuracy on the testing data is 86% which means 86% of the data is correctly predicted.

**Precision:** Precision on the testing data is 87% which means that the amount of false positives is low.

**Recall:** Recal on the testing data is 86% which means that the model accurately predicts 86% percent of true positives.

**F1 Score:** F1 Score on the testing data is 86% which means overall accuracy of the model is 86%. The minimum f1 score on is 63% and the maximum f1-score is 98% (we have 98% accuracy on classifying Trousers).

As the training and testing data metrics do not differ a lot, we can say that we don't have a risk of overfitting.
