# Image Classification of American Sign Language Dataset

![ASL Example](./American%20Sign%20League%20picture.png)

In this repository, we explore image classification using the American Sign Language (ASL) dataset. The dataset contains images of hands forming letters in ASL, allowing us to build a model to recognize these letters.

## Objectives

- Prepare image data for training
- Create and compile a simple model for image classification
- Train an image classification model and observe the results

## Dataset

The [American Sign Language alphabet](http://www.asl.gs/) consists of 26 letters. However, the dataset excludes the letters 'j' and 'z' as they involve movement. The dataset is available on Kaggle and is a great resource for deep learning projects.

## Loading and Preprocessing Data

We load the ASL dataset using Pandas and preprocess it. The images are in CSV format, and after loading, we prepare the training and validation datasets.

## Visualizing the Data

We visualize the ASL images using Matplotlib. Each image is reshaped from a 1D array of 784 pixels to a 2D array of 28x28 pixels. We also normalize the pixel values to be between 0 and 1.

## Building and Training the Model

We build a sequential neural network model using Keras. The model architecture includes dense layers with ReLU activation functions and a softmax output layer. We compile the model and train it using the training and validation datasets.

## Discussion: Overfitting

The model's training accuracy may be high, but the validation accuracy might be lower. This could be due to overfitting, where the model memorizes the training data without generalizing well to new data. Overfitting is a common issue that we'll address in the next sections.

## Next Steps

This project provides a foundational understanding of image classification. To delve deeper, we can explore more advanced models like Convolutional Neural Networks (CNNs) to enhance accuracy and generalize better.

---

**Note**: This project is part of a larger learning experience. To continue exploring more sophisticated models and techniques, stay tuned for further sections and notebooks.

