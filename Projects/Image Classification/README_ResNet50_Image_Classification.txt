
# ResNet50 Image Classification

## Overview
This project utilizes the powerful ResNet50 model, a deep convolutional neural network, for image classification. It aims to predict and categorize images based on the ImageNet database, providing an insight into the capabilities of deep learning in image recognition tasks.

## Features
- **ResNet50 Integration**: Leverages the TensorFlow implementation of ResNet50 pre-trained on the ImageNet dataset.
- **Image Processing**: Includes routines for loading and preprocessing images to the format required by ResNet50.
- **Batch Predictions**: Processes a batch of images from a specified directory and predicts their classes.
- **Results Storage**: Predictions for each image are saved in a designated results directory, with detailed class probabilities.

## Requirements
- TensorFlow
- Keras
- NumPy

## Installation
Clone the repository and install the required packages:
```sh
git clone https://github.com/your_username_/resnet50-image-classification.git
cd resnet50-image-classification
pip install tensorflow keras numpy
```

## Usage
1. Place your images in the `./images63/` directory.
2. Run the script to perform image classification.
3. Check the `./results/predictions/resnet50/` directory for predictions.

### Example
```python
from model import ResNet50Classifier
classifier = ResNet50Classifier()
classifier.run_classification()
```

## Contributing
Your contributions are welcome! Feel free to fork the repository and submit pull requests.

