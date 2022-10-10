# Differentially-private domain generation algorithm detection

[Background](#background)
[Technologies](#technologies)
[Future Work](#future-work)

## Background

This work demonstrates a novel means of producing a differentially-private machine learning model for the purpose of domain-generation algorithm detection. We demonstrate the process by which a trained model can be made quantifiably private against adverserial analysis. This work is based on the work of Ricardo Maia involving DGA-detection in a secure multi-party protocol. 

## Technologies

* Tensorflow-Privacy (contains bolt-on differential privacy auto diff engine and SGD variant)
* Keras

## Future Work

Differentially-private stochastic gradient descent alters the procedure by which queries are made over a dataset at the cost of performance enhancements when performed in a non-private training setting. Future work remains to demonstrate the viability of vectorized approaches to the differentially private training process such that parallel hardware can be leveraged. 

