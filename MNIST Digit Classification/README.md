Digit Classification MNIST 

Working with the MNIST dataset to classify handwritten digits using the Softmax model.

Dataset: 
Working with the MNIST dataset. This is a dataset of handwritten digits. 
Each example is a 28-by-28 pixel grayscale image of a handwritten digit. 
A vectorized representation of the images is used, converted to a 784-dimensional integer vector with values
between 0 (white) and 255 (black). The dataset is provided in the data folder. 

• Training set of 20000 examples
• Validation set of 10000 examples
• Test set of 10000 examples (no labels are provided)

Each set is divided equally among 10 classes. In addition to the normal training set of 20000
examples, there is a small training set of only 30 examples (3 per class) included to investigate
the effect of dataset size on training a classifier in this domain.

The first task was to implement and compute the negative log-likelihood of the model class.
The second task was to implement and compute the gradient calculation of the model class. 
Then plots of the confusion matrix and weight visualizations were created for the analysis and comparing of the two data regimes (small and large). 
Finally, the performance of the best model was shown, after tuning the hyperparameters. 
