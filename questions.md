
# Model

## Machine Learning
[A Few Useful Things to Know about Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)

- VC dimension
- PAC

### Performance measures
- TP, FP, TN, FN
- precision, recall, accuracy
- AP, mAP

### Representation
- lr vs svm vs decision tree vs dnn
- assumption
- overfitting vs underfitting
- bias vs variance
- ensemble methods(bagging, boosting and stacking)
- imbalance between classes
- cross validation

### Evaluation
- loss
- cross entropy loss and softmax
- cross entropy loss vs mse

### Optimization

- first-order optimization or second-order optimization algorithm
- optimization strategy, sgd, momentum, rmsprop, adam, adamw

## Deep Learning

### General
- difference between all kinds of norm(in, ln, bn, gn)
- bn vs se
- alpha in bn, how to prune network using alpha
- bn vs whitening
- eps and momentum in bn
- loss normalization: use batch-wise norm vs sample-wise norm or others
- interpreting confidence scores: process each class separately or not
- the use of activation function
- relu vs sigmoid
- backpropagation
- class imbalance
- vanishing gradient problem

### Convolutional neural networks
- assumption of convolutional neural network
- why convolutional layer not fc layer
- features fusion methods
- dilated conv vs deconvolution
- receptive field calculation
- why we don't need bias in conv when networks are pluged in bn
- backpropagation of pooling layer and bn
- exponential moving average
- translation invariance and translation equalvariance
- the implementation of dilated conv in tf
- why no bn in fc layer

### Object detection 
- one stage vs two stage
- ssd vs yolo vs retinanet
- roi align vs roi pooling
- anchor matching strategy
- positive, negative, ignore anchor
- objective function
- how to detect small objects
- how to get better detection performance
- how to get faster detection model
- why multi-scale and how
- data augmentation
- train from scratch
- freeze part of layers or not
- the difference between face detection and pedestrain detection
- roi align -> roiconv
- why anchor free
- SNIP, tridentnet

# Programming basics
- leetcode
- copy vs deepcopy in python
- *((*int)(&(int a = 2;)))
- 0.35 / 0.05

# Linux basics
- command
- tool chain, include, library, environment variable
