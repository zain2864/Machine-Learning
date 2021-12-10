Spam Detection with Decision Trees

Included are all the data files in the data folder, the python notebook file, and python file.

Applying decision trees to the problem of determining whether or
not an email is spam. Specifically using the AdaBoost algorithm to do so. 

Dataset:
The dataset has been split into a training set of 3000 examples, along with validation and 
test sets. Each example has 57 continuous valued features, mostly indicating
the frequencies of words such as “money”, “free”, and “credit”. Other features include the
length of the longest run of capital letters, and some character frequencies (e.g., “$” and “!”).
The labels are binary, and the annotation is slightly noisy (there are two pairs of training
examples with exactly the same features, but different labels).

Some tasks include: Implementing the Decision Trees, 
Implementing the AdaBoost algorithm, 
Train decision trees on the spam dataset with various hyperparameter settings, and
Train an ensemble on the spam dataset with various hyperparameter settings.
