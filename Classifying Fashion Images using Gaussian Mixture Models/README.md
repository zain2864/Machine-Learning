Classifying Fashion Images Using Gaussian Mixture Models 

Included are all the data files in the data folder, the python notebook file, and python file.

Goal is to use Gaussian Mixture Models in a generative classifier for classifying images into
the ten Fashion classes.

Dataset: Fashion MNIST dataset is used. To speed things up and reduce the memory footprint of the code,
we have reduced the dimension of the problem by resizing the images to 16×16 pixels, from the original 
28×28. While this does lead to some reductionin accuracy for many methods, the images are still possible 
to classify pretty accurately.

Some tasks include: Gaussian log probability computation, Mean Initialization, Implementing Expectation Maximization 
(EM) Algorithm, Implementing covariance matrix updates for both the diagonal and the non-diagonal cases, 
evaluating the accuracy of the GMM-based generative classifier on a dataset, and Fitting a GMM for each class. 
