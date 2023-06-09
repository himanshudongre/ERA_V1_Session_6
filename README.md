# ERA_V1_Session_6

## PART 1
Here we calculate backpropogation equations by hand for a small network as given below
![Network and Its backpropagation equations](S6/back_prop_calculation.jpg)

- The excel sheet with the calculation is present [here](S6/backprop.xlsx)

Below is the loss function graph when training the above neural network for different learning rates:
- `Learning Rate = 0.1`\
![Error Function Graph With LR0.1](S6/Error_LR0.1.jpg)

- `Learning Rate = 0.2`\
![Error Function Graph With LR0.2](S6/Error_LR0.2.jpg)

- `Learning Rate = 0.5`\
![Error Function Graph With LR0.5](S6/Error_LR0.5.jpg)

- `Learning Rate = 0.8`\
![Error Function Graph With LR0.8](S6/Error_LR0.8.jpg)

- `Learning Rate = 1.0`\
![Error Function Graph With LR1.0](S6/Error_LR1.0.jpg)

- `Learning Rate = 2.0`\
![Error Function Graph With LR2.0](S6/Error_LR2.0.jpg)

Observation:
As we can see from the above graph, with increase in learning rate, the loss reduces faster i.e the neural network given above is able to converge quickly.
However, this is a very simple model. Selecting an appropriate learning rate is crucial for successful model training, and being cautious in this choice
can help avoid issues such as slow convergence, unstable dynamics, poor generalization, and getting stuck in suboptimal solutions.

## PART 2
Here we write an MNIST classifier model with following constraints:
- 99.4% validation accuracy
- Less than 20k Parameters
- You can use anything from above you want. 
- Less than 20 Epochs
- Have used BN, Dropout,
- (Optional): a Fully connected layer, have used GAP.

- Code for this is present [here](S6/ERA_Session_6.ipynb)

