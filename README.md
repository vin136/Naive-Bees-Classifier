# Naive-Bees-Classifier
This project will be done in 3 iterations.This is the first experiment where i used resnet32 with pretrained imagenet weights to fine tune the model to predict between two classes of the bees.I have used fastai library as it is the only one with implentation of cyclical learning rates.I would also try to implement one toy model where i would train from scratch.

1.Iter 1:Here we will do transfer learning on pretrained resnet weights(imagenet).We will be using fastai library(which is the only library that has good implementation of [cyclical learning rates.](https://arxiv.org/abs/1506.01186).If some of the details are not evident from the code ,i suggest to go through [fastai github](https://github.com/fastai/fastai/tree/master/fastai)

2.Iter 2:Here we will be trying to train from scratch.May be again a resnet type architecture(with skip connections),in iter 1,i have taken random sample for validation but the dataset is unbalanced so we got to tweak that a bit.

3.This can be used to finally increase the accuracy by using test dataset where we take the labels those predicted by  already trained network and again train for a iteration.We can also do model averaging.
