# Fruit and Vegetable Classification

This repository contains code for a fruit and vegetable classification system using machine learning techniques. The system is designed to identify various fruits and vegetables from images provided as input.

## Dataset
The dataset used for training the model is not included in this repository due to its large size. However, it can be obtained from (https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition), or you can use your own dataset following the same structure.

## Model
The model architecture used in this project is a convolutional neural network (CNN) implemented using TensorFlow and Keras. The trained model achieves a high accuracy in classifying fruits and vegetables.

## Usage
To train the classification model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Obtain the dataset and place it in a directory named `data` within the repository.
4. Run `train.py` to train the classification model.

After training, you can use the trained model to make predictions on new images using the `predict.py` script.

Replace `path_to_image` with the path to the input image and `path_to_trained_model` with the path to the trained model.

## Evaluation
Evaluation metrics such as accuracy, precision, recall, and F1-score are logged during training and can be used to assess the performance of the model.

## Output Image

![WhatsApp Image 2024-04-28 at 2 21 41 AM](https://github.com/Kashyapriya/Tic-tac-toe/assets/95755693/51447a61-9f3b-4bdd-8f2b-52bf155052af)
