Using CNTK to create a multi-layer neural network to classify MNISt dataset.

This code is adapted from the CNTK tutorials:
1. https://github.com/Microsoft/CNTK/blob/v2.0/Tutorials/CNTK_103A_MNIST_DataLoader.ipynb
2. https://github.com/Microsoft/CNTK/blob/v2.0/Tutorials/CNTK_103C_MNIST_MultiLayerPerceptron.ipynb

To execute the code:

$az ml execute start -c docker ./mnist_cntk.py