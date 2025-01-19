# Machine-Learning-with-Python-Projects---Cat-and-Dog-Image-Classifier

This repository contains the Google Colab notebook used for the project **Cat and Dog Image Classification**. The project is part of a task to implement and train a Convolutional Neural Network (CNN) to distinguish between images of cats and dogs.

## Overview

The goal of this project is to classify images of cats and dogs with a machine learning model built using TensorFlow and Keras. The notebook demonstrates the process of data preparation, model building, training, and evaluation. This task includes essential steps for an image classification pipeline such as image augmentation, handling overfitting, and visualizing results.

### Key Features

- **Image Generators**: Utilized `ImageDataGenerator` to preprocess images for training, validation, and testing. This includes rescaling pixel values and applying data augmentation techniques to enhance training data.
- **Convolutional Neural Network (CNN)**: Designed and trained a CNN using Keras Sequential API. The model consists of several Conv2D and MaxPooling2D layers, followed by fully connected layers.
- **Performance Visualization**: Plotted graphs for accuracy and loss to monitor model performance over training epochs.
- **Prediction and Results**: Predicted classes for test images and displayed the results with confidence scores for each image.

## Project Achievements

- Successfully classified images of cats and dogs with 66% accuracy.
- Addressed overfitting using data augmentation techniques.
- Visualized predictions for 50 test images, displaying confidence percentages for each classification.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Open the Google Colab notebook from the link provided or upload the notebook to your Colab environment.
3. Follow the instructions in the notebook to train the model and generate predictions.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- Matplotlib
- Google Colab

## Google Colab Notebook

Access the Google Colab notebook [here](https://colab.research.google.com/drive/14rPAPQ_tC9BX_DpTkZciWT1OJysMlr1p#scrollTo=la_Oz6oLlub6&uniqifier=4).

## Contribution
This project is part of a machine learning challenge, and all improvements or strategies are designed to meet the project requirements. Contributions are not necessary for submission, but improvements are welcome for future versions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
