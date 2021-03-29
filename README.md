# Lifelong-Learning-churn-prediction-torch
The implementation of lifelong learning concept on sequential two tasks of churn prediction. This concept emphasizes learning for developing knowledge continuously while also overcoming the catastrophe of forgetting. CL/LL also works specifically only in multilayer perceptron/backpropagation based models that known for the ability to generalize


Mechanism regularization which I implement to tackle down the forgetting problems that this concept suffer from. This mechanism add constraint on the update of weights for protect previous knowledge. The techniques, Elastic Weight Consolidation, Uses a regularization-based mechanism to add a constraint on certain weight determined by importance to protect previously learned knowledge. The trick is to lock weight used to solve the first task when training for a new task with EWC.


This implementation reference from: 
1. “Overcoming catastrophic forgetting in neural networks” by Google Deepmind Team (James Kirkpatrick, and others)
https://arxiv.org/pdf/1612.00796.pdf
2. The reference for EWC framework with pytorch code from https://github.com/shivamsaboo17/Overcoming-Catastrophic-forgetting-in-Neural-Networks

This repo also directly connected to : https://github.com/fionisarnen/without-LL-churn-prediction

> You can find the details of this project through my publication: https://ieeexplore.ieee.org/document/9212924

