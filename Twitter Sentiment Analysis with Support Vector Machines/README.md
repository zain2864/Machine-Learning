Twitter Sentiment Analysis with Support Vector Machines

Included are all the data files in the data folder, the python notebook file, and python file.

Binary sentiment classification:
We will consider the problem of predicting sentiment 
from tweets. We will formulate this as a binary classification problem where one class 
consists of positive or neutral tweets and the other class consists of negative tweets.

Dataset: 
The tweets are regarding US airline service quality. The provided dataset of a
few thousand tweets has been manually labeled to reflect these binary sentiment labels.

Vector Representation of Input Text: 
We will represent each tweet by a feature vector based on word occurrences. This representation 
for documents is sometimes called “bag of words” since it discards the ordering of words and treats 
them as interchangeable “tokens” in a bag (document). To skip non-trivial engineering issues, we will
rely on existing packages to do the low-level processing and feature extraction for us. The details are 
addressed in the notebook.
