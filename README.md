# BirdSpeciesClassifierD
A deep learning project for identifying bird species from images using bounding box coordinates.
# Bird Species Classifier

This repository contains a deep learning model designed to classify bird species based on images. The dataset consists of images of 200 bird species, and the model uses a Convolutional Neural Network (CNN) to predict the species based on the provided image and bounding box information.

## Project Structure

- **images/**: Contains the train and test images.
- **train.csv**: CSV file containing the training data (image paths, class labels, bounding boxes).
- **test.csv**: CSV file containing the test data (image paths, bounding boxes).
- **model/**: Directory where the trained model will be saved.
- **predictions.csv**: The CSV file generated by the model containing predictions on test images.
- **model_inference.py**: The Python file where model inference and CSV generation code is present.

## Requirements

The code is implemented in Python and requires the following packages:

- `tensorflow`
- `numpy`
- `opencv-python`
- `pandas`
- `matplotlib`

To install the dependencies, you can use the following command:

```bash
pip install tensorflow numpy opencv-python pandas matplotlib
