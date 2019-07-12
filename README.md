# image_generation

```
packages required:-
1) tensorflow
2) keras
3) numpy
4) matplotlib
```

Create some dataset and provide the path of the dataset in the path present in the python script.

For this code we will use the universal MNIST dataset, which is basically a collection of digits. Use the link below to dowload the dataset which is of specific use to tensorflow programs

https://chromium.googlesource.com/external/github.com/tensorflow/tensorflow/+/r0.7/tensorflow/g3doc/tutorials/mnist/download/index.md



As output, you will obtain a latent space distribition and a grid of digits in the form of a marix.

Before running the code, here are some key points to remember-

- Use the dataset API for reading and transforming the data to train our model using an iterator.
- We have defined functions for encoder and decoder separately in just a few lines of code.
- The cost function is made up of two different parts, the log likelihood and the KL divergence term.