# Machine Learning Lab
> Exploring meachine learning techniques and algorithms. Including clustering algorithms, perceptron and natural language processing.


# Contents
* [Clustering Algorithms](https://github.com/arashsm79/machine-learning/tree/main/clustering-algorithms):
Clustering the ORL dataset using DBSCAN, K-Means, Agglomerative (Single Link, Complete Link, Group Average) and evaluating the results using rand index implemented from scratch.

* [Perceptron and Kernel Methods](https://github.com/arashsm79/machine-learning/tree/main/perceptron-and-kernel-methods): 
Running perceptron on the airline satisfaction dataset and experimenting with kernel methods using an implementation of kernelized perceptron from scratch and kernel approximation.

* [Comment Classification using NLP techniques](https://github.com/arashsm79/machine-learning/tree/main/comment-classification-nlp):
Classifying Reddit comments that are about physics, chemistry and biology.
  - First, we preprocess the corpus using regex and nltk's tokenization and lemmatization
  - Then we use word2vec to create a representation for each word
  - after that, we cluster the representations in order to find the words that are close together in terms of their meaning
  - We then replace all the worlds of each cluster with the representative word of that cluster in the corpus. (this effectively makes sure that all the words in a cluster take the same spot in the bag of words vector).
  - Finally, we create a representation for each comment using bag of words and TF-IDF and try to classify the test data set.
