# MNIST Digit Classification with PyTorch

This project implements a neural network using PyTorch to classify handwritten digits from the MNIST dataset. It includes training, evaluation, and visualization components.

## Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- OpenCV

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/mnist-digit-classification.git
    cd mnist-digit-classification
    ```

2. Install the required packages:
    ```bash
    pip install torch torchvision numpy matplotlib opencv-python
    ```

## Usage

1. **Training and Evaluating the Model**:
    - Load and preprocess the MNIST dataset.
    - Define, compile, and train the neural network model.
    - Evaluate the model and report the accuracy.

2. **Visualize Weights of the First Layer**:
    - Visualize the weights of the first layer after training.

3. **Predict Custom Digit**:
    - Preprocess custom digit images to the required input size (28x28) using OpenCV.
    - Predict the digit using the trained model.

## Explanation

1. **Model Architecture**:
    - The model is a simple feedforward neural network with three fully connected layers.
    - Input layer: 784 units (28x28 pixels).
    - Hidden layers: 128 and 64 units with ReLU activation.
    - Output layer: 10 units for 10 digit classes (0-9).

2. **Training Process**:
    - The model is trained using the Adam optimizer and cross-entropy loss.
    - Training is performed for 5 epochs with a validation split.
    - Loss and accuracy are printed during training and evaluation.

3. **Visualization**:
    - The weights of the first layer are visualized after training.
    - Custom digit images can be inputted, and the model will predict the digit.


