# Happy-Smile
Detecting Whether a person is Smiling or Not

** Test Accuracy: 98% **

Pytorch Framework

## Dataset: https://www.kaggle.com/iarunava/happy-house-dataset<br />
This dataset can be used to solve the Happy House problem. Where, we allow a person to enter the house only if he/she is smiling! So, a smile detector!<br />
The train set has 600 examples. The test set has 150 examples.<br />
Source: This dataset is gathered from the Deep Learning Specialization - Convolutional Neural Network Course - Week 2 - Happy House Exercise.<br />


Input: batch Size * 3 * 64 * 64
<br />
Activation function : ReLU

Used 3 CNN layers:<br />
1.128, 3x3 <br />
2.256, 2x2, dropout=0.25<br />
3.64, 3x3, dropout=0.4<br />

Lastly, 2 affine layers are used to get 2d output before using Softmax function to calculate the probability for each class.  

Class:<br />
0 - No Smile<br />
1 - Smile<br />
