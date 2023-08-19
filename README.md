# Bird-Or-Drone-Classification
Developed a CNN model to classify bird and drone images. Enhanced accuracy with data augmentation. Evaluated using ROC curves and confusion matrices. Optimized threshold for binary classification.

# Bird vs. Drone Image Classifier
Classify bird and drone images using a Convolutional Neural Network (CNN) model. Enhance accuracy through data augmentation. Evaluate the model using ROC curves and confusion matrices. Optimize threshold for binary classification.

## Table of Contents

- [Project Description](#project-description)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributions and Feedback](#contributions-and-feedback)

## Project Description

This project aims to develop a machine learning model that can accurately differentiate between images of birds and drones. The CNN model is trained on a dataset of labeled bird and drone images, with an emphasis on data augmentation to improve accuracy. The project evaluates the model's performance using ROC curves and confusion matrices, and determines an optimal threshold for binary classification.

## Key Features

- CNN model for image classification
- Data augmentation techniques for improved accuracy
- Evaluation using ROC curves and confusion matrices
- Optimal threshold determination for binary classification

## Project Structure

- `data/`: Directory containing image datasets (train, validation, test), It contains three sub folders.
- `data/train`:It contains multiple images of birds and drone(pre classified) to train the machine learning model.This file was too big to be directly uploaded to github. So, I am attachine uploading this file and attaching the link [here](https://drive.google.com/drive/folders/1cWrShKLJzhk2S8dUKk0hGw2mk4aM7vBn?usp=sharing).
- `Validation`:This zip file contains some sample classified images to validate the model.
- `test`:This zip file contains sample images to test the machine learning model.
- `bird or drone classification.ipynb`: CNN code to make the ML model and train and test it.This is the main code written in python.

## Getting Started

1. Clone this repository: `git clone https://github.com/your-username/bird-drone-classifier.git`
2. Set up a virtual environment and install dependencies: `pip install -r requirements.txt`
3. Organize your image dataset in the `data/` directory (train, validation, test subdirectories).
4. Adjust model hyperparameters and configurations in the relevant script.
5. Run `train.py` to train the model and save checkpoints.
6. Run `evaluate.py` to evaluate model performance and visualize results.

## Contributions and Feedback

Contributions and feedback are welcome! If you encounter any issues or have suggestions for improvement, feel free to create a pull request or open an issue.
