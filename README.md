# CNN-for-cifar10-dataset
Building a Convolutional Neural Network in TensorFlow 2.0 for cifar10 dataset

From the first model, we get the accuracy of approximately 73% in test dataset but approximately 82% in the training dataset which shows a sign of overfitting.

From this improved model, we get the accuracy of almsot 77% in test dataset and approx 80% in the training dataset which is better than the previous model we train without dropout which has shown sign of overfitting. The accuracy for train dataset decreases but overfitting is reduced. Using dropout and increasing the epoch form 5 to 15, the accuracy for test dataset also increases and overfitting also reduced. Further improvement can also be done if want to implement similar projects in production.

The descripton about the implementation is in the colab notebook itself.
