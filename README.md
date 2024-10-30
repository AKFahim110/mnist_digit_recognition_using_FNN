# MNIST Digit Recognition using Feedforward Neural Network (FNN)

This project implements a Feedforward Neural Network (FNN) for classifying handwritten digits from the MNIST dataset. The model consists of 3 hidden layers with ReLU activation, followed by an output layer.

## Key Features

- **Model Architecture**: Configurable input, hidden, and output layer sizes.
- ![CNN Architecture](https://miro.medium.com/max/2824/1*uAeANQIOQPqWZnnuH-VEyw.jpeg)
- **Training and Validation**: Utilizes PyTorch's `nn.CrossEntropyLoss` for loss calculation and `torch.optim.SGD` for optimization.
- **Evaluation Metrics**: Performance is evaluated using accuracy on the validation set.

## Results

After training, the model achieved the following validation performance:
- **Validation Loss**: 0.4383
- **Validation Accuracy**: 87.60%

## Usage

1. Clone the repository.
2. Install required libraries (e.g., PyTorch).
3. Run the training script to train the model on the MNIST dataset.
4. Evaluate the model using the provided validation function.

## License

This project is licensed under the MIT License. Feel free to contribute or modify!
