---
layout: post
author: bogdan
title:  "Deep learning glossary"
---


I'm writing this post to aid me in my quest to learn machine and deep learning. It will serve as a quick reference for machine learning terms that I regularly encounter. I find the best way to learn something is to write it down in my own understanding, which has the added benefit of also being useful to someone else. This will be a very high level look into these terms as I'm writing this at the very start of my ML journey. The terms are not in alphabetical order.


**Machine learning vs deep learning** - in some places I've encountered the two terms as synonyms, however I like this differentiation which refers to deep learning in the context of neural networks. It does make sense to me, as the neural networks usually consist of multiple layers. In contrast, machine learning can be used as a general term for a number of different algorithms which learn from data and make predictions.

**Artificial neural networks** - artificial here separates the computer science neural networks from the actual neural networks in our brains. It's a bit redundant, but is often times used. Its typical attributes include:

* a collection of connected units (neurons)
* each connection between the neurons can transmit a signal between them
* the receiving neuron processes the signal and signals the downstream neurons connected to it
* organized in layers; a typical organization is input -> hidden -> output layers
* each neuron from the preceding layer is connected to all neurons of the next layer

**Activation function** - defines the output of the neuron given a set of inputs

**Weights** - a weight coefficient is placed on each connection between neurons. These weights determine how much influence the input will have on the output. Neural networks are initialized with random weights.

**Loss function** - calculates the difference between the neural network is predicting versus what the label is i.e the error between the prediction and the ground truth.

**Optimization function** - optimizes the weights, minimizes the loss function.

**Learning rate** - how big the step for optimization is. The higher the number, the bigger the step, which also means the model will be trained faster.

**Overfitting a model** - the model is fitted will on the training data, but does not perform well on the validation data. This means the model doesn't generalize well. Possible improvements include: more training data, data augmentation.

**Underfitting** - can be observed when metrics (loss, accuracy) are poor. Often when the data is too complex for the model. Possible improvements: add more features to the data if possible.

**Supervised learning** - when the training data is labeled.

**Unsupervised learning** - when the training data is not labeled.

