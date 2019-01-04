# Happy-Smile
Detecting Whether a person is Smiling or Not

Test Accuracy: 98%

Pytorch Framework

Dataset: https://www.kaggle.com/iarunava/happy-house-dataset
This dataset can be used to solve the Happy House problem. Where, we allow a person to enter the house only if he/she is smiling! So, a smile detector!
The train set has 600 examples. The test set has 150 examples.
Source: This dataset is gathered from the Deep Learning Specialization - Convolutional Neural Network Course - Week 2 - Happy House Exercise.



Input: batch Size * 3 * 64 * 64

Activation function : ReLU

Used 3 CNN layers:
1.128, 3x3
2.256, 2x2, dropout=0.25
3.64, 3x3, dropout=0.4

Lastly, 2 affine layers are used to get 2d output before using Softmax function to calculate the probability for each class.

Class:
0 - No Smile
1 - Smile