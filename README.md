Rice Images CNN Projects

Welcome to the CNN Projects repository! This repository contains various Convolutional Neural Network (CNN) projects developed for image classification tasks. Each project is designed to demonstrate different techniques and approaches using CNNs for different datasets.
Table of Contents

    Introduction
    Projects
        Rice Classification WIth tensorflow and keras
        Rice Classification WIth Pytorch
    Installation
    Usage
    Contributing
    License

Introduction

Convolutional Neural Networks (CNNs) are powerful tools for image recognition and classification tasks. This repository showcases various CNN projects that aim to solve different image classification problems. Each project includes code, datasets, and detailed explanations to help you understand and implement CNNs effectively.
Projects


Rice Classification

    Description: This project classifies different types of rice grains using CNNs. The dataset consists of images of five types of rice: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.
    Dataset: The dataset is divided into training, validation, and test sets.
    Techniques Used: Data augmentation, CNN architecture, early stopping, learning rate reduction.
    Framework: TensorFlow/Keras

Project 2

    Description: The same dataset with other model. I have used Pytorch as the second approach.
    Dataset: The dataset is divided into training, validation, and test sets.
    Techniques Used: Data augmentation, CNN architecture, early stopping, learning rate reduction.
    Framework: Pytorch


Installation

To run the projects in this repository, you need to have Python and the required libraries installed. Follow the steps below to set up your environment:

    Clone the repository:



git clone https://github.com/mohmdhmedi//Rice_Images_Classification_CNN.git
cd Rice_Images_Classification_CNN

    Create a virtual environment:



python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

    Install the required libraries:



pip install -r requirements.txt

Usage
Each project is contained within its own directory. Navigate to the project directory and run the code as follows: (as an example)



cd Rice-Classification
python train_model.py

Make sure to follow the instructions provided in each project's README file for specific usage details.
Contributing

Contributions are welcome! If you have any improvements, bug fixes, or new projects to add, please fork the repository and create a pull request. Make sure to follow the contribution guidelines.
