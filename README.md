# MNIST Digit Classification using Neural Network (Jupyter Notebook)

This project implements a neural network from scratch within a Jupyter notebook to classify handwritten digits from the MNIST dataset. The notebook includes the code for building, training, and testing a neural network with various manually-created layers to achieve classification accuracy on the MNIST dataset.

## Project Overview

Contained within a Jupyter notebook, this project entails:

- Loading and preprocessing the MNIST dataset.
- Creating a neural network with customized layers.
- Training and testing the network to classify digits.

## Neural Network Architecture

The neural network architecture is constructed within the Jupyter notebook and involves different layers:

- **Convolutional Layer:** Extracts features using convolutional operations.
- **Activation Layers (e.g., Relu):** Applies nonlinear transformations to the data.
- **Pooling Layers (e.g., Maxpooling):** Reduces spatial dimensions.
- **Dimension Layer:** Reshapes the data to fit the network.
- **Dense Layer:** Fully connected layer for classification.
- **Softmax Layer:** Outputs probabilities for each class.

## How to Use

The Jupyter notebook contains step-by-step instructions:

1. **Dataset Preparation:**
   - Loading the MNIST dataset.
   - Preprocessing the data, limiting examples per digit.

2. **Network Configuration:**
   - Customizing the layers and their parameters in the notebook.

3. **Training:**
   - Training the network using the prepared dataset.
   - Adjusting hyperparameters (e.g., learning rate, number of iterations).

4. **Evaluation:**
   - Evaluating the trained network on the test dataset.
   - Calculating metrics such as accuracy and error rates.

## Notebook Contents

The notebook file (`MNIST_Classification_Neural_Network.ipynb`) contains the complete code and explanations for each step of the process.

## Results and Visualizations

The notebook showcases the results with plots displaying training and testing errors, as well as accuracy metrics over the training iterations.

## Requirements

The notebook requires Python (version X.X), NumPy, Matplotlib, and other dependencies listed in `requirements.txt`.


## License

This project is licensed under the MIT license. See [LICENSE](LICENSE) for more details.