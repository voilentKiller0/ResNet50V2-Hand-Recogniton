# Indian Sign Language Recognition with ResNet50V2

## Project Overview

This Python project utilizes Keras, TensorFlow, and the Mediapipe library to create a real-time Indian Sign Language recognition system. The model is based on the ResNet50V2 architecture and is trained on the Indian Sign Language dataset obtained from Kaggle.


## Table of contents




## Getting Started

### Prerequisites
* Python 3.x installed on your device or use Google Colab
* Install required libraries :
```
pip install tensorflow keras mediapipe opencv-python
```

### Installation
Clone the repository to your local machine:
```
git clone https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton.git
```

## Model Training

### Dataset
The model is trained on the Indian Sign Language dataset obtained from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/prekshapalva/indian-sign-language).

### Training Procedure
Code and Details about the training procedure, hyperparameters, and data preprocessing can be found in the [Python file](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/blob/main/Train%20and%20Create%20Model.ipynb).

## Result

### Model History while train

![image](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/assets/55941465/005163c4-4009-4e0f-8a91-dcd00460ee8a)

![image](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/assets/55941465/08f9b39c-443e-4576-8a1c-e5cb63d93757)

### Model Accuracy on test data-set

![image](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/assets/55941465/4c4e4d3f-6f0a-4f3f-aa6e-1e05e6143a0e)


## Usage

After create the model, Run all the cell of [Live Hand Recognition.ipynb](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/blob/main/Live%20Hand%20Recognition.ipynb)
This code uses your computer's camera to capture real-time video and recognizes Indian Sign Language gestures using the trained ResNet50V2 model.

## About ResNet50-V2 [🔗](https://datagen.tech/guides/computer-vision/resnet-50/#:~:text=The%2050%2Dlayer%20ResNet%20architecture,with%201%C3%971%2C256%20kernels.)


![image](https://github.com/voilentKiller0/ResNet50V2-Hand-Sign-Recogniton/assets/55941465/e4b24cdd-ad7d-4848-966d-ab48de3965ed)


### Why use of ResNet50-v2

1. A robust backbone model called ResNet is utilised often in various computer vision tasks.
2. ResNet employs skip connections to transfer output from one layer to another. This aids in reducing the issue of disappearing gradients.
3. You may load ResNet 50 that has already been trained using Keras, or you can write ResNet by yourself.
4. ResNet50-V2 is advance and efficient version of ResNet50.
