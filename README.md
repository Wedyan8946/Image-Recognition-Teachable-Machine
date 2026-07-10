# Image Recognition Project using Teachable Machine and Python

This project aims to train an AI model to distinguish between cats and dogs using Google's Teachable Machine, and run it using a Python script.

## Steps Performed:
1. Model Training: Opened the Teachable Machine tool, created two classes (Cat and Dog), added images to train and test the model, and confirmed the prediction accuracy within the website.
2. Model Export: Exported the model in TensorFlow -> Keras format and downloaded the model files (`keras_model.h5` and `labels.txt`).
3. Environment and Execution: Used the Google Colab environment and wrote a Python script that calls the TensorFlow and Pillow libraries to process the test image and pass it to the model.
4. Result: The code successfully recognized the image and predicted the class (Dog) with a confidence score of approximately 95.6% (`0.9563052`).

## Repository Contents:
* keras_model.h5: The trained model weights file.
* labels.txt: A text file containing the class names.
* main.py: The Python script used to run the model and make predictions.
* img.jpg: The test image used for prediction.
* output.png: A screenshot showing the model's prediction output inside Google Colab.
* task 2 png 1.png: A screenshot of the Google Teachable Machine interface showing the trained classes (Cat & Dog) and the initial model evaluation.
