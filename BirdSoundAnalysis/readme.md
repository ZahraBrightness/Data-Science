#Abstract
'''
This study classifies the most common bird species in the Seattle area through the implementation of Neural Networks.
Utilizing spectrograms derived from 10 sound clips of various lengths for each of the 12 bird species. This classification problem is examined 
through a binary classification approach on two selected species, a multi-classification using all 12 species, and classification on an unlabeled test set.
The binary classification model using the CNN neural architecture and RNN is conducted on the two selected species of Blue Jay and Steller’s Jay the model
is optimized and tuned through various parameters resulting in the best-performing model with 16 batch sizes and 20 epochs giving an accuracy of 77% on the test set and 76% on the training.
Various CNN models are also trained on the train set of the 12 species and the model’s performance is evaluated through metrics like loss validation, accuracy, and validation accuracy, 
the optimal model with an accuracy of 58% on the train set and 87% on the training set.
The best-performing model of the multi classification problem is then used for the classification of the unlabeled data set presenting Western Meadowlark species
to be mostly detected with being present in the top 5 five species that are identified in all three audio set.
'''
