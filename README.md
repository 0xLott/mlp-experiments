# MLP Experiments with Fashion-MNIST

This repository contains experiments with a Multilayer Perceptron (MLP) on the [Fashion-MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist) dataset. The implementation is based on the [Dive Into Deep Learning](https://d2l.ai/) original Jupyter Notebook for **Multilayer Perceptrons**.  

## Experiments
The goal of these experiments is to analyze the impact of different **hidden layer sizes (`num_hiddens`)** and **learning rates (`lr`)** on model performance.  

### Modifications tested
- `num_hiddens`: 64, 512, 2048 and 4096
- `lr`: 0.01, 0.1, 0.5

### Results summary
- Lower `num_hiddens` leads to underfitting, while very high values cause overfitting. `num_hiddens = 512` produces the most balanced model. 
- Small `lr` results in slow learning and very low accuracy, while high `lr` can cause instability.

## References
- [Original Jupyter Notebook from d2l](https://colab.research.google.com/github/d2l-ai/d2l-pytorch-colab/blob/master/chapter_multilayer-perceptrons/mlp-implementation.ipynb) 
- [Implementation of Multilayer Perceptrons](https://d2l.ai/chapter_multilayer-perceptrons/mlp-implementation.html)
