## IEMS469 HW4 AutoML
The report is shown in assignment4_report.pdf.
The code and result are presented in the notebook [assignment4.ipynb](assignment4.ipynb).
The training results and experiment log are saved in the folder assignment4_result. 

## IEMS469 HW3 FedAvg
### Part 1
The report is shown in assignment3_report.pdf.
The code and result are presented in the notebook [assignment3.ipynb](assignment3.ipynb).
The training model and experiment log are solved in the folder assignment3_result. 
### Part 2
The report is shown in assignment3_part2_report.pdf.
The code and result are presented in the notebook [assignment3_part2.ipynb](assignment3_part2.ipynb).
The training model and experiment log are solved in the folder assignment3_part2_result. 

## IEMS469 HW2 Deep Q-Learning
The code and result are presented in the notebook [assignment2.ipynb](assignment2.ipynb).
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
