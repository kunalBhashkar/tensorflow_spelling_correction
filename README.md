## Spelling Correction
The purpose to create this project is if we give input as wrong sentence then it will automatically correct and will give an output as right sentence.
## Data Set
I have taken data from http://www.gutenberg.org/ebooks/search/?sort_order=downloads which is composed of twenty popular books.

## Model

This model is designed using grid search to find the optimal architecture, and hyperparameter values. The best results, as measured by sequence loss with 15% of our data were created using a two-layered network with a bi-direction RNN in the encoding layer and Bahdanau Attention in the decoding layer.

#Command to get output on Tensorboard
tensorboard --logdir=path/to/log-directory