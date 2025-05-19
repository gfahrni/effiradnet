# EffiRadNet
EffiRadNet is an EfficientNet-based model for fast binary classification of radiological images with easily distinguishable feature


## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Training](#training)
- [License](#license)


## Overview
EffiRadNet is a lightweight convolutional neural network designed for binary classification tasks on radiological images where distinguishing features are clear. 

## Usage


## Dataset
This project expects input radiological images that are easily classifiable into two categories. 
Example structure:

/training-dataset
    /class_0
        image_1.png
        image_2.png
        ...
    /class_1
        image_3.png
        image_4.png
        ...


/testing-dataset
    /class_0
        image_1.png
        image_2.png
        ...
    /class_1
        image_3.png
        image_4.png
        ...


## Training and Testing
EffiRadNet is optimized for quick convergence on relatively simple binary classification problems.

### Key Features:
- All-in-one implementation (training and testing) in a single Jupyter notebook
- Easy customization of hyperparameters directly in the code
- Efficient training process with automatic model saving

### Training Process:
1. The code will locate the training folder at the specified path
2. Model training begins using the configured parameters
3. Upon completion, the trained model is saved as a `.pth` file (filename specified in the code)

### Testing Process:
1. Loads the pre-trained model (`.pth` file) from the specified path
2. Automatically processes each image in the testing dataset
3. Performs classification and outputs results

## License
This project is licensed under the MIT License.
