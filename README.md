![GPU Server Concept](gpu_server_concept.png)

# NO_SLEEP_GPU_PYTORCH

## Introduction
`NO_SLEEP_GPU_PYTORCH` is designed to maximize the utilization of GPU servers. 
This project uses a simple MNIST dataset to train a neural network, **ensuring that your GPU server remains active.**

## Installation
To use this project, you need Python and the following libraries:
- PyTorch
- torchvision
- numpy
- tqdm

It is recommended to install these in a virtual environment. 
You can install the necessary libraries using pip:

`pip install torch torchvision numpy tqdm`


## Usage
To execute the project, simply run the following command:

`python3 MNIST_train.py`

This command automatically downloads the MNIST dataset and utilizes all available GPUs to train the neural network.

## Features
- **No local dataset is needed.**
- **All available GPUs are automatically used.**
- **Simple yet effective neural network training to keep the GPU server active.**

## License
This project is distributed under the MIT License.
