# Simple-Neural-Network

##### Steps to build a Neural Network in NumPy



## Assignment Overview
In this assignment, you will be developing a basic neural network from scratch using Python. The goal is to understand the fundamental components of a neural network by implementing the crucial processes that drive its learning capabilities.

You will fill in the `.......` sections with the necessary code that corresponds to the outlined tasks. Each section requires you to consider mathematical formulations and dimensions of the variables used, which will help reinforce your understanding of how data flows through the network and how various components interact.

**Important Sections:**

1. **Loading the Dataset (Input and Output)**  
   This section involves reading and preprocessing a dataset that the neural network will learn from. You will load features (inputs) and labels (outputs) that the model will try to predict.

2. **Architecture of the Model (# Input, Hidden and Output Neurons)**  
   Here, you will define the structure of the neural network. It is essential to determine the number of neurons in the input layer (which corresponds to the number of features in your dataset), the hidden layer(s) (which will be responsible for learning complex representations), and the output layer (which will provide the final predictions).

3. **Initializing Weights for All Layers**  
   In this section, you will set up the initial weights and biases for the neurons. Proper initialization is crucial for ensuring that the learning process starts effectively, avoiding issues such as vanishing or exploding gradients.

4. **Implementing Forward Propagation**  
   Forward propagation is where you compute the output of the network given its inputs and current weights. By applying activation functions, you will pass the inputs through the network, layer by layer, to obtain the final prediction.

5. **Implementing Backward Propagation**  
   Backward propagation is the process of updating the weights based on the error between the predicted output and the actual labels. You will compute gradients of the loss function with respect to the weights and use these to make adjustments that minimize the error.

6. **Train the Model for n Epochs**  
   This section will involve iterating over the training data for a specified number of epochs, applying forward and backward propagation to refine the model's weights. During training, you will monitor the loss to evaluate the model's performance and convergence.
