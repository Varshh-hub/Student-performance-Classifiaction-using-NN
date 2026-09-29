# Student Performance Classification using Neural Network

A beginner-friendly **Neural Network built from scratch using Python and NumPy** to predict whether a student is likely to **Pass or Fail** based on study-related features.

The main goal of this project was to understand the **working and training process of a Neural Network from the ground up**, without relying on frameworks such as TensorFlow or PyTorch.

## Technologies & Concepts Used

* **Python** – Used to implement the complete neural network and training process.
* **NumPy** – Used for numerical computations, matrix operations, and handling model parameters.
* **Dense Layers** – Used to build the basic structure of the neural network and pass information between layers.
* **ReLU** – Used in the hidden layer to add non-linearity and allow the network to learn patterns from the input data.
* **Sigmoid** – Used in the final layer to convert the model output into a probability for the binary Pass/Fail classification.
* **Binary Cross-Entropy** – Used as the loss function to measure the difference between the predicted and actual labels.
* **Backpropagation** – Used to calculate gradients and determine how the model parameters should be adjusted.
* **Gradient Descent** – Used to update the weights and biases and minimize the loss during training.
* **Learning Rate** – Controls the size of each update made to the model parameters.
* **Epochs** – Defines how many times the model repeats the training process over the dataset.

## How I Built the Model

I developed the neural network step by step instead of using a pre-built deep learning library.

1. Prepared the dataset and separated the **features (`X`)** from the **target (`y`)**.
2. Initialized the **weights and biases** for each layer.
3. Created a **hidden Dense layer with 4 neurons**.
4. Applied **ReLU activation** to the hidden layer.
5. Added an **output Dense layer with 1 neuron**.
6. Applied **Sigmoid activation** to generate the final probability.
7. Calculated the **Binary Cross-Entropy loss** to measure the model's error.
8. Performed **backpropagation** to calculate the required gradients.
9. Applied **gradient descent** to update the weights and biases.
10. Repeated the process across multiple **epochs** until the network learned from the training data.

## What I Learned

Building this project from scratch helped me understand the **fundamentals of Neural Networks at a practical level**.

Through this project, I learned:

* How **weights and biases** are used to make predictions
* How **forward propagation** moves data through the network
* How **activation functions** help a neural network learn non-linear patterns
* Why **ReLU** is commonly used in hidden layers
* Why **Sigmoid** works well for binary classification
* How **Binary Cross-Entropy** measures classification error
* How **backpropagation** calculates gradients
* How **gradient descent** updates model parameters
* How a neural network improves its predictions by **minimizing loss over multiple epochs**
* How the different components of a neural network work together during training

## Key Takeaway

This project gave me a hands-on understanding of how a **Neural Network is structured, trained, and optimized internally**. Building it with NumPy helped me understand the concepts behind deep learning before moving on to **PyTorch and more advanced Deep Learning projects**.

## Author

### Varsha A

AI & ML Graduate | Aspiring Data Scientist & ML Engineer | Python | SQL | Machine Learning | Deep Learning | GenAI
