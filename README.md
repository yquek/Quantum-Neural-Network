# Quantum-Neural-Network
An implementation of the NISQ neural network described in Farhi and Neven (1802.06002) in Google's cirq programming language.  
Currently, our neural network is able to replicate the subset parity function on bitstrings (the first application analyzed in the paper). We are working to make it classify MNIST digits.

![QNN_diagram](https://user-images.githubusercontent.com/20964090/55030073-c8a7bb80-4fc8-11e9-809e-e738ddf7d4e7.png)

(Schematic of proposed quantum neural network, taken from arXiv 1802.06002)

This notebook has the following dependencies:
Python 3
numpy 1.14.6
cirq 0.4.0
scipy 1.1.0
