# Bike-Sharing-Patter-Prediction-with-NeuralNet
Developed as coursework for Udacity Deep Learning Nanodegree.
In this project, I built a neural network to predict daily bike rental ridership.

## Further Explanation
The Neural network was built from "scratch", using only NumPy to assist. The goal of this project is to understand what happens behind the neural network before diving deeper into other tools like PyTorch and Tensorflow.

## Results
The project meets the specifications, which are:
- All the code in the notebook runs without failing, and all unit tests pass.
- The sigmoid activation function is implemented correctly
- The forward pass is correctly implemented for the network's training.
- The run method correctly produces the desired regression output for the neural network.
- The network correctly implements the backward pass for each batch, correctly updating the weight change.
- Updates to both the input-to-hidden and hidden-to-output weights are implemented correctly.
- The number of epochs is chosen such the network is trained well enough to accurately make predictions but is not overfitting to the training data.
- The number of hidden units is chosen such that the network is able to accurately predict the number of bike riders, is able to generalize, and is not overfitting.
- The learning rate is chosen such that the network successfully converges, but is still time efficient.
- The number of output nodes is properly selected to solve the desired problem.

## Conclusion
The predictions given by the model are quite accurate but since the dataset is less it is overtrained.






