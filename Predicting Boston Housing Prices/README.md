Working with the Boston Housing dataset, in which the task is to predict median home prices in various areas of the Boston suburbs from a variety of features.
In the task, the assumption was used that it is much worse to overestimate the price of a house than to underestimate it (e.g., to avoid making an offer that’s too high). 
Technically, it is expressed as an asymmetric squared loss. 

The Model:  Consider fitting polynomial regression models to predict house prices y from observations/measures x.

First task was implementing the gradient descent function. Experimenting with models and optimization parameters, fit polynomial 
models of degrees 1 (linear), 2 (quadratic), and some others to the training set. 
And then using the validation set to select one of the models that is optimal. 

Second task was implementing and computing the asymmetric loss function and its gradient.
Using the asymmetric loss with α = 0.05, fitting polynomial models (of degrees 1, 2, ...) to the training set. 
Similarly, this was also done to the symmetric loss case.
Afterward a selection of the model was made using the validation set for optimality. 

Last task was to evaluate the two chosen models (one trained with symmetric loss and the other
trained with asymmetric loss) on the test set. For each model, computations of the mean symmetric
loss and the mean asymmetric loss were used to determine the relative merits of both models. 
