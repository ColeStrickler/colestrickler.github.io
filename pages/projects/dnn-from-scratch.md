---
layout: post
---

See full project and source code here: [Neural Nets From Scratch](https://github.com/ColeStrickler/ML-FromScratch/tree/main/src/dnn).

This project is a primitive deep neural network framework from scratch in raw C++. The framework supports training via backpropagation and also the ability to parse and load Tensorflow weights. The project also has a data pipeline for the MNIST dataset which I used to test the framework implementation. 

Planned features
*   Optimizations in both inference and training. We can use vector extensions and optimized matmuls. Maybe even CUDA if we're feeling frisky
*   Convolutional layers

![dnn](/assets/img/DNN.jpg)