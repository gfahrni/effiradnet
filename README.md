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

/dataset
    /class_0
        image_1.png
        image_2.png
    /class_1
        image_3.png
        image_4.png


## Training
EffiRadNet is optimized for quick convergence on relatively simple binary classification problems.
You can adjust the model architecture or hyperparameters in the `configs/` directory.


## License
This project is licensed under the MIT License - see the LICENSE file for details.
