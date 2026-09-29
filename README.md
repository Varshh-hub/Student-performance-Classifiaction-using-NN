# Student Performance Classification using Neural Network

A simple **Neural Network built from scratch using Python and NumPy** to classify whether a student will **Pass or Fail** based on study-related features.

This project was built to understand the **fundamentals of Neural Networks and how they learn**, without using a deep learning framework.

## What I Used & Why

* **Python** – Used as the main programming language for building the model.
* **NumPy** – Used for matrix operations, weights, biases, forward propagation, backpropagation, and parameter updates.
* **Dense Layers** – Used to connect the input features to the hidden layer and then to the output.
* **ReLU Activation** – Used in the hidden layer to introduce non-linearity and help the network learn more complex patterns.
* **Sigmoid Activation** – Used in the output layer because this is a binary classification problem. It converts the output into a probability between 0 and 1.
* **Binary Cross-Entropy Loss** – Used to measure how far the predicted probability is from the actual Pass/Fail label.
* **Backpropagation** – Used to calculate how much each weight and bias contributed to the prediction error.
* **Gradient Descent** – Used to update the weights and biases so that the model gradually reduces its loss.
* **Learning Rate** – Controls how large each parameter update is during training.
* **Epochs** – Determines how many times the model goes through the training process.

## How I Built It

The neural network was built step by step from scratch:

1. **Prepared the student data** and separated the input features (`X`) and target labels (`y`).
2. **Initialized weights and biases** for the neural network.
3. Built the **first Dense layer** with 4 neurons.
4. Applied **ReLU activation** to the hidden layer.
5. Built the **output Dense layer** with 1 neuron.
6. Applied **Sigmoid activation** to produce the Pass/Fail probability.
7. Calculated the **Binary Cross-Entropy loss**.
8. Implemented **backpropagation** to calculate the gradients.
9. Used **gradient descent** to update the weights and biases.
10. Repeated this process for multiple **epochs** so the network could learn from the data.

## How It Works

```text
Input Features
      ↓
Dense Layer (4 Neurons)
      ↓
ReLU Activation
      ↓
Dense Layer (1 Neuron)
      ↓
Sigmoid Activation
      ↓
Pass/Fail Probability
      ↓
Binary Cross-Entropy Loss
      ↓
Backpropagation
      ↓
Gradient Descent
      ↓
Update Weights & Biases
      ↓
Repeat for Multiple Epochs
```

## What I Learned

This project helped me understand what happens **inside a Neural Network** instead of directly using a framework.

I learned:

* How **neurons, weights, and biases** work
* How **forward propagation** generates predictions
* Why **ReLU** is used in hidden layers
* Why **Sigmoid** is suitable for binary classification
* How **Binary Cross-Entropy** calculates classification loss
* How **backpropagation** calculates gradients
* How **gradient descent** updates model parameters
* How a neural network **learns by repeatedly reducing its error**
* How the different components of a neural network work together during training

## Key Takeaway

Building this Neural Network from scratch gave me a practical understanding of the **core architecture, mathematics, and training process of neural networks** and created a strong foundation for moving into **PyTorch and more advanced Deep Learning projects**.

## Author

### Varsha A

AI & ML Graduate | Aspiring Data Scientist & ML Engineer | Python | SQL | Machine Learning | Deep Learning | GenAI
