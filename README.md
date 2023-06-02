# Assignment_05

## Description

This repository contains the implementation of a machine learning model for Assignment_05. It includes the following files:

- `model.py`: This file contains the implementation of  model used in the project.
- `utils.py`: This file contains utility functions for training and testing the model, as well as the train and test data loaders.
- `s5.ipynb`: This Jupyter Notebook file demonstrates how to call the training and test loops from `utils.py` and import the model from `model.py` for training and evaluation.

## Files

### `model.py`

The `model.py` file contains the implementation of the machine learning model used in this project. It defines the structure of the neural network and the forward pass method. The model architecture consists of several convolutional layers (`Conv2d`) and linear layers (`Linear`), with ReLU activations and max pooling operations. The final output is passed through a log softmax activation function to obtain the predicted probabilities. You can modify this file to customize the model architecture or add any other required functionalities.

### `utils.py`

The `utils.py` file provides utility functions for training and testing the machine learning model. It includes functions for loading and preprocessing the data, creating train and test data loaders, defining the training loop, and evaluating the model. The `train` function performs the training of the model using the provided train data loader and optimizer. The `test` function evaluates the model on the test data loader. Additionally, there are helper functions for calculating the number of correct predictions and maintaining the training and testing statistics. You can modify this file to adjust the data loading process or implement different training and testing mechanisms.

### `s5.ipynb`

The `s5.ipynb` Jupyter Notebook file demonstrates how to utilize the functionalities provided by `model.py` and `utils.py` to train and evaluate the machine learning model. It imports the model from `model.py`, sets up the train and test data loaders using functions from `utils.py`, and executes the training and testing loops using the imported functions from `utils.py`. By running this notebook, you can train the model on the provided train data and evaluate its performance on the test data. Feel free to modify the notebook to suit your specific needs.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Jaydeep-singh-1999/Assignment_05.git
   ```
2. Customize the `model.py` file to define your desired model architecture.
3. Modify the `utils.py` file to suit your data preprocessing, loading, and training/testing requirements.
4. Run the `s5.ipynb` notebook to train and evaluate the model.

Feel free to explore and experiment with different model architectures, training strategies, and hyperparameters to achieve the best performance for your specific task.

## License

## Acknowledgments

## Contributing

## Contact

 Jaydeepsinghchouhan1999@gmail.com
