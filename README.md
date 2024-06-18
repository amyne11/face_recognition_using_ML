Face Recognition Using Machine Learning

This project implements face recognition using machine learning techniques. The provided dataset includes face images of 40 subjects, with 10 images per subject, each having 32×32 pixels and 256 grey levels per pixel.

## Table of Contents
- [Introduction](#introduction)
- [Preparation](#preparation)
- [Approach](#approach)
  - [Data Preparation](#data-preparation)
  - [Model Training](#model-training)
  - [Evaluation](#evaluation)
- [Future Work](#future-work)
- [Contributing](#contributing)

## Introduction
This project aims to recognize faces using L2-regularized least squares for classification tasks. The dataset includes 400 images of faces, split into training and test sets.

## Preparation

### Setting up
Import the necessary functions and libraries, load the data, and visualize the dataset to understand its structure and content.

### Visualising the dataset
Observe the faces stored in a data matrix using visualization functions to display single and multiple face examples.

### Splitting into the train and test sets
Normalize pixel values and partition the data into training and test sets, ensuring an appropriate split for training and evaluation.

## Approach

### Data Preparation
- Load data and labels using custom functions.
- Normalize pixel values to [0, 1].
- Partition data into training and test sets with a 5:5 split per subject.

### Model Training
Implement L2-regularized least squares (L2-RLS) for multi-class classification, with a focus on selecting the best lambda value through hyperparameter selection.

### Evaluation
- Evaluate model accuracy using a confusion matrix.
- Visualize correctly and incorrectly classified faces.

## Future Work
- Expand the dataset for better robustness.
- Develop a real-time face recognition system.
- Explore advanced architectures and techniques like transfer learning.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions or improvements.

