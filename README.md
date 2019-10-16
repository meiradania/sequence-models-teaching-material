# Sequence models 

This repo contains a walk-through RNNs (recurrent neural networks), the family of neural networks for processing sequential data.


The material focuses implementation using Keras [Sequential API](https://keras.io/getting-started/sequential-model-guide/) and is derived from or largely inspired by:
+ [sequence notes by Adam Green](https://github.com/ADGEfficiency/teaching-monolith/tree/master/sequences)
+ [Keras Intro by Mike Irvine](https://github.com/sempwn/keras-intro)
+ [Machine Learning Mastery's Keras Tutorial](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/) 
+ [Understanding LSTM Networks from Cohlah's blog](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)


Original content developed and maintained by Dania Meira - [meira.dania@gmail.com](mailto:meira.dania@gmail.com)

Distributed under the [MIT license](https://github.com/meiradania/sequence-models-teaching-material/blob/master/LICENSE.md).




## Getting started with Keras

Install [Tensorflow](https://www.tensorflow.org/install/) and [Keras](https://keras.io/) in a new conda enrironment:
```bash
$ conda create -n keras_cpu -y pip jupyterlab pandas scikit-learn matplotlib
$ conda activate keras_cpu
$ pip install --ignore-installed --upgrade tensorflow
$ pip install keras
```

## Table of Contents

[00-keras-intro-sequential-api.ipynb](00-keras-intro-sequential-api.ipynb)
- Keras Sequential API first look
- Binary classification problem
- Toy Dataset
- Simple multi-layer perceptron with one hidden layer


[01-keras-introduction-mnist.ipynb](01-keras-introduction-mnist.ipynb)
- Keras Sequential API
- Multi-classification problem
- MNIST dataset


[02-recurrent.ipynb](02-recurrent.ipynb)
- recurrent neural network - motivations & mechanics
- character level language modeling


[03-lstm.ipynb](03-lstm.ipynb)
- LSTMs - motivations & mechanics
- GRUs
- sin wave prediction

  

## Further Resources
- [Directory of tutorials and open-source code repositories for working with Keras](https://github.com/fchollet/keras-resources)
- [deeplearning.ai Sequence Course](https://www.coursera.org/learn/nlp-sequence-models/)
- [Keras Blog](https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html)
- [How to configure the number of layers and nodes in a neural network](https://machinelearningmastery.com/how-to-configure-the-number-of-layers-and-nodes-in-a-neural-network/)
- [Time series prediction with LSTM](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/)
