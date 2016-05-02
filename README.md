# Language Classifier

### The purpose of this project is to build a program that when given a file, is able to determine the coding language it is written in.

### The program uses the built-in glob module to read from a data set of files written in various languages. The data is then split into training and testing subsamples. Then the scikitlearn module is used to transform the data files into a data object that consists of unique words and their count.  Then, a naive bayes training analysis is performed to link the training features to their final classification. Lastly, we use our testing subsample to test the accuracy of our model.

### In addition to the method described above, two additional methods were attempted to see if the classification could be improved.  The second method used the regular expressions module to better specify which word characters were pulled out of the data as features.  The third method attempts to build my own system for pulling features out of the data.
