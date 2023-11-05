## IEMS469 HW2 Deep Q-Learning
The code and result are presented in the notebook [assignment2.jpynb](assignment2.jpynb).
For MsPacman game, I tried two realization of deep Q network:
1. State as a flatten vectors + 3-layer multi-layer perception (MLP) networks.
2. State as a 2-D image + 3-layer CNN
Corresponding hyperparameters may be found in neural network definition blocks.

## IEMS469 HW1 Policy Grandient

### Requirements
- gym==0.26.2
- matplotlib==3.4.3
- numpy==1.19.5
- scipy==1.7.1
- torch==2.0.0

You may install all the packages by the [requirement.txt](requirement.txt).

### Hyperparameters
The policy is realized by a 2-layer fully connected neural networks with the following parameters for both simulations (i.e., cart-pole and pong gama):
- Learning Rate: 1e-3
- \# of layers: 3
- \# hidden dimensions: 200
- layer 1 activate function: ReLU
- layer 2 activate function: SoftMax
- $\gamma$ (cart-pole): 0.99
- $\gamma$ ()

### Demos
The demo showing the effectiveness of the implementation is shown in the notebook [assignment1.jpynb](assignment1.jpynb).

### Results
The training plots of cart-pole and pong game are shown in the folder [./results](./results)