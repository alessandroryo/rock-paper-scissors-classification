# Rock-Paper-Scissors Classification

This repository contains a machine learning project designed to classify images of hand gestures into one of three categories: rock, paper, or scissors. The project demonstrates the use of convolutional neural networks (CNNs) for image classification tasks, utilizing Python and TensorFlow.

## Table of Contents

- [Rock-Paper-Scissors Classification](#rock-paper-scissors-classification)
	- [Table of Contents](#table-of-contents)
	- [Project Overview](#project-overview)
	- [Dataset](#dataset)
	- [Model Architecture](#model-architecture)
	- [Training](#training)
	- [Results](#results)
	- [Contributing](#contributing)
	- [License](#license)
	- [Contact](#contact)

## Project Overview

The goal of this project is to build a model that can accurately classify images as either rock, paper, or scissors. The model is trained on a dataset of labeled images, and its performance is evaluated based on its accuracy in predicting the correct hand gesture. This project serves as a practical application of convolutional neural networks in the field of image recognition.

## Dataset

The dataset used in this project consists of images labeled as either "rock", "paper", or "scissors". The images are preprocessed to a consistent size and format before being fed into the neural network for training. The dataset includes a diverse set of hand gestures to ensure robust model performance.

- **Number of images**: Approximately 2,188 images.
- **Image format**: PNG, with each image resized to 300x200 pixels.

## Model Architecture

The model is built using a convolutional neural network (CNN) with the following architecture:

- **Input Layer**: Handles input images of size 300x200x3 (height x width x channels).
- **Convolutional Layers**: Multiple layers to capture spatial features from the images.
- **Pooling Layers**: Max-pooling layers to reduce the spatial dimensions and computational load.
- **Fully Connected Layers**: Dense layers for final classification.
- **Output Layer**: A softmax layer that outputs probabilities for the three classes: rock, paper, and scissors.

## Training

The model is trained using the following parameters:

- **Optimizer**: Adam optimizer
- **Loss Function**: Categorical cross-entropy
- **Metrics**: Accuracy
- **Epochs**: 20 (adjustable)
- **Batch Size**: 32 (adjustable)

The training process includes data augmentation to improve the model's generalization ability.

## Results

The model achieves an accuracy of over 95% on the test dataset, demonstrating its effectiveness in classifying hand gestures for the game of rock-paper-scissors.

## Contributing

Contributions are welcome! If you have any suggestions for improvements or find any bugs, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact

For any questions or inquiries, please contact me via email:

- **Email**: <alessandroryo@gmail.com>
